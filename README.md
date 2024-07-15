# Credit Risk Classification

## Credit Risk Analysis Report

### Purpose of the Analysis

The goal of this analysis is to create a logistic regression model to predict whether a loan is high-risk or healthy. This helps banks make better lending decisions and manage risk.

### Financial Information and Predictions

We used the following information to classify each loan:

- **Loan Size**: Amount borrowed.
- **Interest Rate**: Annual percentage charged as interest.
- **Borrower Income**: Annual income of the borrower.
- **Debt to Income Ratio**: Monthly debt payments divided by monthly income.
- **Number of Accounts**: Total number of credit accounts.
- **Derogatory Marks**: Negative records like late payments.
- **Total Debt**: Total debt owed.
- **Loan Status**: 0 for healthy loans, 1 for high-risk loans.

### Variable Prediction Counts

The data includes:

- **Healthy loans (0)**: 75,000
- **High-risk loans (1)**: 2,500

### Prediction Results Data

- **True Positives (TP)**: 563 (High-risk correctly predicted)
- **False Negatives (FN)**: 56 (High-risk incorrectly predicted as healthy)
- **False Positives (FP)**: 102 (Healthy incorrectly predicted as high-risk)
- **True Negatives (TN)**: 18,663 (Healthy correctly predicted)

### Stages of the Machine Learning Process

1. **Data Collection & Preparation**: Loaded and split data into training and testing sets.
2. **Model Selection**: Chose Logistic Regression for binary classification.
3. **Model Training**: Trained the model on the training data.
4. **Model Prediction**: Made predictions on the testing data.
5. **Model Evaluation**: Evaluated using confusion matrix and classification report.

### Methods Used

- **Logistic Regression**: Effective for predicting binary outcomes like loan status.

## Results

### Machine Learning Model: Logistic Regression

- **Accuracy**: 0.99
- **Precision**:
  - Healthy loans (0): 1.00
  - High-risk loans (1): 0.85
- **Recall**:
  - Healthy loans (0): 0.99
  - High-risk loans (1): 0.91

## Summary

### Summary of the Results

The model has a high accuracy of 99%, meaning it is very reliable in predicting loan status.

### Precision Insights

- **Healthy Loans (0)**: Precision is 1.00, meaning all predicted as healthy are actually healthy.
- **High-Risk Loans (1)**: Precision is 0.85, meaning 85% predicted as high-risk are correct.

### Recall Insights

- **Healthy Loans (0)**: Recall is 0.99, meaning it correctly identifies 99% of healthy loans.
- **High-Risk Loans (1)**: Recall is 0.91, meaning it correctly identifies 91% of high-risk loans.

### Model Recommendations

- **Reliability**: The model is highly reliable for assessing loan risk.
- **Risk Management**: It accurately identifies high-risk loans, helping manage credit risk.
- **Customer Satisfaction**: It ensures most good applicants are approved.

The logistic regression model is a valuable tool for predicting loan status, with excellent performance in accuracy, precision, and recall. It is recommended for use in credit risk assessment.
