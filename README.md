# House Price Prediction Using Regression Model

This project focuses on machine learning model to predict house prices for house buyers and house sellers.

The value of a house is more than just location and square footage. Houses have several features that make up it's value. We are going to take advantage of all the features to make accurate predictions about the price of any house.

# Methods Used
- Data Cleaning
- Data Wrangling
- Feature Engineering
- Data Visualisation
- Machine Learning (Linear Regression, Random Forest Regression, Decision Tree Regression, KNeighbor Regression)

# Technologies Used
- Python
- Jupyter
- Numpy, Pandas, Seaborn, Matplotlib
- Scikit Learn

# Project Description
- Project began with fetching of data from csv file [Data](https://github.com/ShamikRana/House-Price-Prediction-Using-Regression-Model/blob/main/House_Data.csv) downloaded from Kaggle
- Data is then cleaned by removing null values ,outliers and useless columns
- New features are created like price_per_sqft and data is normalised using MinMaxScaler and StandardScaler
- Dataset is divided in 80:20 ratio as test and train dataset
- Machine Learning algorithms are applied like Linear Regression, Random Forest Regression, Decision Tree Regression, KNeighbor Regression

# Findings
 ![Linear Regressor Finding](https://raw.githubusercontent.com/ShamikRana/House-Price-Prediction-Using-Regression-Model/main/LinearRegressor.png)
 ![Decision Tree Regressor Findings](https://raw.githubusercontent.com/ShamikRana/House-Price-Prediction-Using-Regression-Model/main/DecisionTree.png)
 ![KNeighbor Regressor Findings](https://raw.githubusercontent.com/ShamikRana/House-Price-Prediction-Using-Regression-Model/main/KNeighbor.png)
 ![Random Forest Regressor Findings](https://raw.githubusercontent.com/ShamikRana/House-Price-Prediction-Using-Regression-Model/main/RandomForest.png)
    
- Random Forest Regressor has shown highest accuracy, followed by Decision Tree and KNeighbors Regressor. Linear Regressor has shown lowest accuracy

# How to Use 
- Fork this repository to have your own copy
- Clone your copy on your local system
- Install necessary packages
