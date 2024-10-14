# Project Overview

This project aims to predict customer churn for a bank. Below is the sequence of tasks completed during the project:

## Completed Tasks:

1. **Data Loading**: Loaded training and test datasets containing customer information.
2. **Data Cleaning**: 
   - Removed irrelevant columns ("CustomerId", "Surname", "id").
   - Created age categories ("Youth", "Young Adult", "Adult", "Senior").
3. **One-Hot Encoding**: 
   - Applied One-Hot Encoding to the "Geography", "Gender", and "AgeGroup" columns.
4. **Null Value Removal**: Removed null values from both training and test datasets.
5. **Feature Engineering**: 
   - Created the "BalanceSalaryRatio" feature, which calculates the ratio between the customer's balance and estimated salary.
6. **Model Building**: 
   - Constructed a Logistic Regression model using a pipeline with Polynomial Features and StandardScaler.
7. **Prediction and Saving Results**: Made predictions on the test data and saved the results in a CSV file.
8. **Model Evaluation**: Evaluated the model on the training data using the ROC AUC metric.
