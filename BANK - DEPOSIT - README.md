# Predicting Term Deposit Subscriptions Using Bank Marketing Data

You can access the full [project here](https://eyowhite.com/predicting-bank-deposit-subscriptions-using-machine-learning/).

# Project Overview
This project aims to predict whether clients of a bank will subscribe to a term deposit based on various features from a marketing campaign. 
Dataset

The dataset consists of 45,211 records and 17 features, including client demographics, financial status, and details of previous marketing interactions. The target variable is y, indicating whether the client subscribed to a term deposit (yes or no).

# Project Structure

## 1.	Data Exploration:
      o	Performed Exploratory Data Analysis (EDA) to understand the data distribution and identify key patterns.
      o	Visualized numerical and categorical variables to gain insights into the dataset.
      
## 2.	Data Preprocessing:
      o	Encoded categorical variables.
      o	Split data into training and testing sets.
      o	Applied feature scaling.
      
## 3.	Model Training and Evaluation:
      o	Trained a Random Forest classifier.
      o	Evaluated model performance using confusion matrix, classification report, and ROC-AUC score.
      o	Visualised the ROC curve and confusion matrix.
      
# Results
•	The model achieved an accuracy of 90% and a ROC-AUC score of 0.924, indicating strong performance in distinguishing between clients who will and will not subscribe.
•	Precision and recall for the positive class ("yes") were 63% and 41%, respectively, suggesting the model is better at predicting non-subscribers.

# Recommendations
•	Improve model sensitivity by addressing the class imbalance and exploring alternative algorithms.
•	Enhance feature engineering to capture more nuanced client behaviours.
•	Focus marketing efforts on clients with high predicted probabilities of subscription.

