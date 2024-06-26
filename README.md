# credit-risk-classification

## Overview
- The purpose of this analysis was to create a model via machine learning that would accurately assess an individual borrower's loan risk.

- The information given to the machine learning algorithm were the size of the loan, the interest rate, the borrower's income, the borrower's 
debt to income ratio, the number of accounts belonging to the borrower, and the borrower's total debt.  From this information, the model would 
predict whether the borrower represented a healthy loan or a high-risk loan.

## Results
- Accuracy:  Provides a percentage of correctly predicted values.  Includes both positive and negative predictions.  The prediction is based 
on the total number of samples in the entire data set.  In this model, 99% of all predictions were correct.

- Precision: This tells us what percentage of predicted 0 or 1 values were predicted correctly.

- Recall:  This provides a ratio of predicted 0 or 1 values to the total number of 0 or 1 values in the whole data set.  In this model, of all
true class 1 samples, 89% of those were correctly identified.

## Summary
According to the f1-scores of the classification report, healthy loans were predicted with 100 percent accuracy while high-risk loans were 
predicted with 88 percent accuracy.  The overall accuracy of the model was high at 99% and can be safely recommended for predicting healthy
and high-risk loans.

The loan statuses are binary values - they are either healthy (0) or high risk (1).  If a borrower's loan status is not 'healthy', it can be 
safely assumed that the loan status is high-risk.  Since the healthy loans were able to be predicted with 100 percent accuracy, it would be
recommended to use that class to predict borrowers' loan statuses.  With this model, any prediction that is not 'healthy' can be assumed to be
high-risk.