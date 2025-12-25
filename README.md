📉 Customer Churn Prediction using Machine Learning

(Kaggle Telco Customer Churn Dataset)

📌 Project Overview

Customer churn prediction is a critical business problem for telecom companies. This project uses the Kaggle Telco Customer Churn dataset to build machine learning models that predict whether a customer will churn (Yes/No) based on demographics, subscribed services, and billing information.

To address class imbalance in the dataset, SMOTE was applied to improve model performance and recall for churned customers.

🎯 Objectives

Analyze customer behavior and churn patterns

Handle class imbalance using SMOTE

Build and evaluate machine learning classification models

Identify key features influencing customer churn

📊 Dataset Description

Source: Kaggle – Telco Customer Churn

Total Records: 7,043 customers

Target Variable: Churn (Yes / No)

Feature Categories

Demographics: gender, SeniorCitizen

Account Info: tenure, contract, payment method

Services: phone, internet, streaming services

Billing: MonthlyCharges, TotalCharges

🛠️ Tech Stack

Language: Python

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

imbalanced-learn (SMOTE)

🔍 Methodology

Data Cleaning & Preparation

Handled missing values and incorrect data types

Encoded categorical variables

Exploratory Data Analysis (EDA)

Churn distribution analysis

Service-wise churn trends

Tenure vs churn visualization

Handling Class Imbalance

Applied SMOTE on training data

Balanced churn vs non-churn classes

Model Building

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Model Evaluation

Accuracy

Precision, Recall, F1-score

Confusion Matrix

📈 Results & Key Insights

SMOTE significantly improved recall for churned customers

Customers with month-to-month contracts have the highest churn

Low tenure and high monthly charges are strong churn indicators

Random Forest achieved the best overall performance

