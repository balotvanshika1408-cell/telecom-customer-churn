# Customer Churn Prediction using Logistic Regression
## Project Overview

Customer churn prediction is a crucial task for businesses to identify customers who are likely to stop using their services.
This project implements a machine learning model using Logistic Regression to predict customer churn based on customer demographics, service usage, and account information. 
The model helps organizations take proactive steps to improve customer retention and reduce revenue loss.

## Objectives

1. Analyze customer data to understand churn behavior
2. Build a binary classification model using Logistic Regression
3. Evaluate model performance using appropriate metrics
4. Identify customers with high churn probability

## Machine Learning Approach

1. Algorithm Used: Logistic Regression
2. Problem Type: Binary Classification
3. Target Variable: Churn (Yes / No)

## Technologies & Tools

1. Programming Language: Python
2. Libraries:
3. NumPy
4. Pandas
5. Matplotlib
6. Seaborn
7. Scikit-learn

## Dataset Description

The dataset contains customer-related information such as:

1. Demographic details
2. Subscription and service usage
3. Account information
4. Churn status (target variable)

The dataset is preprocessed to handle missing values, categorical variables, and feature scaling.

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
     .Handling missing values
     .Encoding categorical features
     .Feature scaling
4. Model Training using Logistic Regression

5. Model Evaluation

6. Result Interpretation

 ## Model Evaluation Metrics

The model performance is evaluated using:

1. Accuracy
2. Precision
3. Recall
4. F1-Score
5. Confusion Matrix

These metrics help assess how effectively the model predicts customer churn.

## Model Results

![Confusion Matrix](images/Screenshot (1912).png)

The Logistic Regression model successfully classifies customers into churn and non-churn categories. 
The evaluation metrics indicate that the model performs reasonably well and can assist businesses in identifying high-risk customers for targeted retention strategies.

## Future Scope
The model performance can be further improved by using advanced classification algorithms and handling class imbalance techniques.
