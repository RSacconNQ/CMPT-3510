# CMPT-3510

# Vehicle Price Prediction Project

## Project Overview

This project was developed as part of a machine learning course and aims to build a regression model capable of predicting vehicle prices based on key features such as make, model, mileage, year, engine size, and more. The objective is to assist in understanding which variables influence price and to produce a model that can support data-driven pricing decisions.

## Dataset Summary

- The dataset includes detailed information about various vehicles such as year, mileage, make, model, fuel type, transmission, body style, drivetrain, and color.
- The target variable for prediction is the vehicle's listed price.
- Data was pre-processed to handle missing values, outliers, and inconsistencies in categorical fields.

## Methodology

### 1. Data Cleaning
- Inspected and removed duplicate records.
- Addressed missing values using imputation strategies appropriate to variable types.
- Standardized and normalized column names and data types.
- Detected and removed outliers to enhance model accuracy.

### 2. Exploratory Data Analysis (EDA)
- Analyzed the distribution of numerical features such as price and mileage.
- Investigated relationships between features and the target variable using visualizations and statistical summaries.
- Identified feature correlations and trends that influence vehicle pricing.

### 3. Feature Engineering
- Encoded categorical variables using label encoding.
- Created new features to improve model performance.
- Dropped irrelevant columns that did not contribute to model prediction.

### 4. Model Building and Evaluation
- Implemented and compared multiple regression algorithms:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Evaluated model performance using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)

## Tools and Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for machine learning modeling and evaluation

## Author

Renata 
Machine Learning Student, NorQuest College  

