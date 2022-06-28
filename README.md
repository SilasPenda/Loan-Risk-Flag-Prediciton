# Loan-Risk-Flag-Prediciton
This is a supervised machine learning project using loan customer data to predict customer risk flag based on their Income, Age, Marital Status, Profession, Financial Responsibilities, etc
## Project Guide
In this project i made use of Pandas, Numpy, train_test_split, RandomForestClassifier, StandardScaler, and joblib

This project was carried out using the following steps:
* Importing the necessary libraries 
* Reading CSV into a dataframe
* Cleaning data by
  * Checking for NaN rows 
  * Dropping irrelevant columns
  * Checking for outliers using Z-score
* Creating dummy columns for machine learning
* Grouping dependent and independent variables and scaling the independent variables appropriately
* Train RandomForestClassifier model
* Save model using joblib
* Load model and use for predictions
