# Fraud Detection in Financial Transactions

View the full [project here](https://eyowhite.com/how-to-predict-financial-fraud-using-python/)

# Project Overview
This project focuses on analysing a dataset of financial transactions to identify patterns of fraudulent activities. By applying exploratory data analysis (EDA), feature engineering, and machine learning techniques, we aim to build a robust model that can effectively detect fraudulent transactions. The project includes various stages such as data preprocessing, visualisation, model building, and model evaluation.

# Project Structure

## •	Data Preprocessing:
o	Load the dataset.
o	Convert date columns to appropriate datetime formats.
o	Engineer features such as customer age, transaction hour, day of the week, month, and distance between transaction and merchant locations.

## •	Exploratory Data Analysis (EDA):
o	Univariate and bivariate analysis to understand the distribution of key features like transaction amounts, customer age, and city population.
o	Geospatial analysis to visualise the geographic distribution of transactions and identify fraud hotspots.

## •	Model Building:
o	A Random Forest model is built to classify transactions as fraudulent or non-fraudulent.
o	Model evaluation is conducted using precision, recall, F1-score, and a confusion matrix.

## •	Model Optimisation:
o	Hyperparameter tuning using GridSearchCV to find the best parameters for the Random Forest model.

## •	Advanced Visualisations:
o	Analysis of fraud by time (hour of the day, day of the week, month of the year).
o	Visualisation of the distribution of fraud across different transaction categories.

# Requirements
•	Python 3.x
•	Pandas
•	Matplotlib
•	Seaborn
•	Geopy
•	Scikit-learn

# Results
The Random Forest model achieved high precision and recall in detecting fraudulent transactions, with a nearly perfect F1-score. The model's performance was further improved by hyperparameter tuning. The insights gained from the analysis can be used to implement more targeted fraud prevention measures.

