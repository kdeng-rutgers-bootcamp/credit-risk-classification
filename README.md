# Module 12 Report Template

The Credit Risk analysis is contained in the credit_risk_classification.ipynb file. The original dataset is contained in the Resources folder.

## Overview of the Analysis

The purpose of this analysis is to predict whether a loan is considered healthy, or high-risk.
* The relevant financial information used to predict whether or not a loan is healthy includes: loan amount, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.
* Healthy loans are denoted with a 0, and high-risk loans are denoted with a 1.
* Describe the stages of the machine learning process you went through as part of this analysis.
* The analysis involved splitting off the loan status column, as that was the one that was being predicted. Then, a train-test split was created, and a logistic regression model was fit and used to make predictions.
* The second stage of the analysis involved another logistic regression model trained on oversampled data to ensure equal sizes of both classes.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy: 0.952
  * Precision: class 0: 1.00 class 1: 0.85
  * Recall: class 0: 0.99 class 2: 0.91

* Machine Learning Model 2:
  * Balanced Accuracy: 0.994
  * Precision: class 0: 0.99 class 1: 0.99
  * Recall: class 0: 0.99 class 1: 0.99

## Summary

The second model, created with oversampled training data, performs best. This is because all scores used to evaluate the model saw improvement. This is important, since high-risk loans are the ones that are more important to predict, since it can cause both the client and the institution to lose money.