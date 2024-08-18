# Project Overview

See the full project [here](https://eyowhite.com/how-to-predict-heart-disease-treatment-using-python/).

This project aims to predict treatment types for heart attack patients using machine learning techniques. The dataset comprises demographic, lifestyle, and clinical variables for 1,000 patients, including their age, gender, blood pressure, cholesterol levels, smoking status, presence of diabetes, chest pain type, and the treatment they received. The primary objective is to build a predictive model that can assist healthcare professionals in making informed treatment decisions.

# Project Workflow

## 1.	Exploratory Data Analysis (EDA):
o	Performed initial data exploration, including summary statistics and visualisation of the distributions of numerical and categorical variables.
o	Analysed correlations between numerical variables.
o	Conducted Chi-Square tests to assess relationships between categorical variables.

## 2.	Predictive Modelling:
o	Used a Random Forest classifier to predict treatment types based on the features.
o	Evaluated the model using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
o	Generated a confusion matrix and ROC-AUC curves to visualise model performance.
o	Identified key features contributing to the model's predictions using feature importance analysis.

## 3.	Model Interpretability and Recommendations:
o	Provided insights into the most influential factors affecting treatment decisions.
o	Suggested improvements, including feature engineering, data expansion, and advanced modelling techniques for future work.

# Key Results
•	The Random Forest model achieved modest accuracy in predicting treatment types, with certain health metrics (e.g., blood pressure, cholesterol, age) being the most significant predictors.
•	The model’s performance suggests room for improvement, particularly with more comprehensive data and advanced modelling approaches.

# Recommendations
•	Expand the dataset to include more features and patient records.
•	Enhance data quality through better preprocessing and handling of class imbalances.
•	Explore advanced models and hyperparameter tuning to improve prediction accuracy.
•	Collaborate with clinical experts to validate findings and refine the model.

# Conclusion
This project demonstrates the potential of machine learning in aiding heart attack treatment decisions, though further development and validation are required for clinical application. The insights gained could lead to more personalised and effective patient care strategies.

