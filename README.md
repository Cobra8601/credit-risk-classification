## Overview of the Analysis

This predictive machine learning model was constructed to identify the creditworthiness of borrowers at a lending company. Development of the model utilized the loan size, interest rate, income, debt-to-income, number of accounts with the company, derogatory remarks, and total debt of 77,536 customers to conduct supervised machine learning of customer loan status. A value count demonstrated 75,036 healthy loans and 2500 at-risk loans. The data was split into training versus testing datasets using train_test_split with a random_state of 1. Loan status was utilized in a logistic regression model as the outcome (y), with predictors loan size, interest rate, income, debt-to-income, number of accounts with the company, derogatory remarks as (x). A confusion matrix was employed to compare the actual versus predicted values.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
