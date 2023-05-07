# Usa-house-predict--linear-regression



#Readme


This repository contains a Python script that predicts the average price of a house based on several features using a linear regression model. The script utilizes the pandas, numpy, seaborn, and scikit-learn libraries for data handling, analysis, visualization, and machine learning.

#Dataset


The script uses the "USA_Housing.csv" dataset, which contains information about houses in the USA. The dataset includes the following columns:



Avg. Area Income: Average income of the residents in the area

Avg. Area House Age: Average age of houses in the area

Avg. Area Number of Rooms: Average number of rooms in houses in the area

Avg. Area Number of Bedrooms: Average number of bedrooms in houses in the area

Area Population: Population of the area

Price: Price of the house

Address: Address of the house (not used in the script)



#Usage


Make sure you have the required libraries installed: pandas, numpy, seaborn, and scikit-learn.

Download the "USA_Housing.csv" dataset and place it in the same directory as the Python script.

Run the script using a Python interpreter or a Jupyter notebook.

The script will read the dataset, perform data preprocessing by dropping the 'Address' column, and split the data into training and testing sets.

A linear regression model will be trained on the training set.



The script will prompt you to enter the values of the following features for which you want to predict the house price:



Average area income in $

House age in years

Area of the room

Number of rooms

Average population of the area you are looking at

After providing the input values, the script will predict the average price of the house and display the result in Rupees.

You will be asked if you want to continue predicting prices for more houses. Enter 'y' to continue or 'n' to exit the loop.



#Results


The model's accuracy is evaluated using the coefficient of determination (R-squared) score on the test set. In the provided example, the model achieved an R-squared score of approximately 0.9164, indicating a good fit to the data.


Please note that the predicted prices are displayed as integers in Rupees.


Feel free to modify the code and dataset to suit your needs and experiment with different machine learning models for price prediction.


Enjoy exploring and predicting house prices!
