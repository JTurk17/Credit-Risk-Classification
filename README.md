# Credit-Risk-Classification

## Background
The purpose of this project is to to train and evaluate a model based on loan risk. Ultimately we want to build a model that can identify the creditworthiness of borrowers for a peer-to-peer lending services company.

## Credit Analysis Report

### Overview
The purpose of this analysis was to build a logistic regression model that could predict whether someone is a high-risk loan or a healthy loan based on:
- loan size
- interest rate
- borrower income
- debt to income
- number of accounts
- derogatory marks
- total debt

### Resluts
After running the model, I would say we can conclude the model was pretty good. Here are the results of classification report:

- Healthy Loan
  - Precision: 1.00
  - Recall: 1.00
 
- High-Risk Loan
  - Precision: .87
  - Recall: .89
 
- Overall
  - Accuracy: .99
 
### Summary
As we can see from the classification report output, the model performed pretty well. When it comes to the healthy loan the precision and recall were both perfect. This drops slightly when viewing the high-risk loan predicitons, but the scores are still pretty good. Overall the accuracy of 99% is great and I think we can conclude it is a good model.
