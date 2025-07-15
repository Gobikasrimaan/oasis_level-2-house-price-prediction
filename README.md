🏠 House Price Prediction | Oasis Level 2 Project 1

Project Overview:
This is a complete end-to-end House Price Prediction project done as part of Oasis Infobyte Data Science Internship - Level 2 Project 1. The project focuses on predicting house prices using Exploratory Data Analysis (EDA), Data Preprocessing, and Linear Regression model.

Table of Contents:

Introduction
Dataset Information
Exploratory Data Analysis (EDA)
Data Cleaning and Preprocessing
Feature Engineering
Model Building
Model Evaluation
Results
Conclusion

Introduction:
The goal of this project is to predict house prices based on multiple independent features like area, bedrooms, bathrooms, and furnishing status using Python and Machine Learning.

Dataset Information:
Dataset: Housing Dataset from Oasis Infobyte Internship
Records: 545 rows, 13 columns
Target Variable: price
Features: area, bedrooms, bathrooms, stories, parking, and other categorical features like furnishing status, mainroad, etc.

Exploratory Data Analysis (EDA):

Univariate Analysis – countplots, distribution plots
Bivariate Analysis – scatterplots, boxplots
Correlation heatmaps to study relationships between variables

Data Cleaning and Preprocessing:

No missing values
Removed duplicates
One-hot encoding applied to categorical variables using get_dummies()

Feature Engineering:

Categorical columns converted using One-Hot Encoding
Target variable is price
Final feature matrix ready for model training

Model Building:

Linear Regression applied using sklearn
Data split into 80% training and 20% testing

Model Evaluation:
Used four metrics to evaluate model performance:

R2 Score
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)

Results:

Model: Linear Regression
R2 Score: 0.6529
MSE: 1,754,318,687,330.66
RMSE: 1,324,506.96
MAE: 970,043.40

Linear Regression explains approximately 65% variance in house prices with an RMSE of around 13.2 Lakhs.

Conclusion:
EDA provided useful insights about the housing dataset.
Linear Regression showed reasonable performance with ~65% accuracy.
Project successfully completed with data preprocessing, EDA, model building, and evaluation.
