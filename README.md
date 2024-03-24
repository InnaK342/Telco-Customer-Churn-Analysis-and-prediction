# Telco Customer Churn Analysis and Prediction

This repository contains code for analyzing and predicting customer churn for a telecommunications company.

## Dataset

The dataset used in this project is available at [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn). It contains information about customers, including demographic details, services subscribed to, and churn status.

## Project Overview

The project involves the following steps:

1. **Exploratory Data Analysis (EDA)**:
   - Understand the characteristics and patterns present in the dataset through visualizations and descriptive statistics.

2. **Feature Engineering**:
   - Create new features and preprocess the data to prepare it for modeling.
   - A new feature, `MonthlyTotalRatio`, representing the ratio of MonthlyCharges to TotalCharges is created.

3. **Model Building**:
   - Train and evaluate various machine learning models including Logistic Regression, SVM, Decision Trees, and Random Forests to predict customer churn.

4. **Hyperparameter Tuning**:
   - Optimize model parameters using GridSearchCV to improve performance.

5. **Model Evaluation**:
   - Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
   - Confusion matrices are generated to visualize the performance of each model.

