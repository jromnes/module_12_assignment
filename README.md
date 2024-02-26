# Module 12 Assignment: Credit Risk Classification

## Overview of the Analysis

__Purpose of the Analysis:__
The purpose of this analysis is to develop and evaluate machine learning models to predict and identify the creditworthiness of borrowers. This analysis aims to assist in making informed decisions regarding creditworthiness of borrowers.

__Financial Information in the Data and Prediction Target:__
The data contains various financial features related to loans, such as loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, and loan_status. The prediction target is the loan status, with a binary classification of "healthy" (0) or "high-risk" (1).

__Basic Information about the Variables/Data:__
* loan_size: The size or amount of the loan requested by the borrower.
* interest_rate: The rate at which interest is charged on the loan amount, typically expressed as a percentage.
* borrower_income: The income of the borrower, which may be used to assess the borrower's ability to repay the loan.
* debt_to_income: The ratio of the borrower's total debt to their income, often used by lenders to evaluate the borrower's financial health and ability to manage additional debt.
* num_of_accounts: The number of financial accounts (e.g., credit cards, loans) that the borrower has open.
* derogatory_marks: The number of derogatory marks on the borrower's credit report, which may include late payments, defaults, or bankruptcies.
* total_debt: The total amount of debt owed by the borrower across all accounts.
* loan_status: The target variable indicating the loan status, with values typically encoded as:
  * 0: Healthy loan (indicating that the borrower is likely to repay the loan)
  * 1: High-risk loan (indicating a higher likelihood of defaulting on the loan)

## Results

### Machine Learning Model 1 (Original Data):
* Balanced Accuracy Score: __0.9520__
* Precision:
  - Class 0 (Healthy loans): __1.00__
  - Class 1 (High-risk loans): __0.85__
* Recall:
  - Class 0 (Healthy loans): __0.99__
  - Class 1 (High-risk loans): __0.91__

### Machine Learning Model 2 (Oversampled Data):
* Balanced Accuracy Score: __0.9937__
* Precision:
  -  Class 0 (Healthy loans): __1.00__
  - Class 1 (High-risk loans): __0.84__
* Recall:
  - Class 0 (Healthy loans): __0.99__
  - Class 1 (High-risk loans): __0.99__ 

## Summary

Model 2 outperformed Model 1 with a higher Balanced Accuracy score (0.9937 compared to 0.9520). Model 2 also showed improved precision, recall, and F1 score for predicting high-risk loans (1) while maintaining high performance for healthy loans (0). The performance improvement in Model 2 can be attributed to the use of oversampling techniques to address class imbalance, which leads to better classification of high-risk loans. Therefore, Model 2 is recommended for use due to its better overall performance in accurately classifying both healthy and high-risk loans. 
