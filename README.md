Customer Churn Prediction

company's service by analyzing historical data and usage patterns using machine learning.

Overview

This project builds and evaluates machine learning models for predicting customer churn leveraging core features like demographics, subscription history, and usage statistics. Early detection of likely churn enables targeted retention strategies and reduces business revenue loss.

Features

Data cleaning and preprocessing

Exploratory Data Analysis (EDA) and visualization

Feature selection and engineering

Multiple predictive models (Logistic Regression, Random Forest, XGBoost)

Model evaluation using accuracy, precision, recall, F1, ROC-AUC

Churn prediction for new or unseen data

Dataset

Source: Kaggle

Features: Customer ID, demographic details, subscription length, monthly bill, usage metrics, churn flag

Preprocessing: Label encoding, missing value imputation, balancing classes


Results

Achieved high accuracy and recall using Random Forest model.

Model performance metrics:

Accuracy: 85%

Precision: 78%

Recall: 82%

ROC-AUC: 0.88

Feature importance analysis indicated that customer tenure, monthly charges, and number of customer service calls are among the top predictors influencing churn.
Interpretation and visualizations of feature importance are included in the results plots.
