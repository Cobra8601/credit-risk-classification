## Overview of the Analysis

This predictive machine learning model was constructed to identify the creditworthiness of borrowers at a lending company. Development of the model utilized the loan size, interest rate, income, debt-to-income, number of accounts with the company, derogatory remarks, and total debt of 77,536 customers to conduct supervised machine learning of customer loan status. A value count demonstrated 75,036 healthy loans and 2500 at-risk loans. The data was split into training versus testing datasets using train_test_split with a random_state of 1. Loan status was utilized in a logistic regression model as the outcome (y), with predictors loan size, interest rate, income, debt-to-income, number of accounts with the company, derogatory remarks as (x). A confusion matrix was employed to compare the actual versus predicted values.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model
    * Accuracy
      The model supports an accuracy of 99.1%, indicating it to be correct 99.1% of the time.
    * Precision
      The model supports that it is reliably able to predict a healthy loan with 100% precision. At-risk loans        can be reliably predicted with 85% precision.  
    * Recall
      The model supports that it is reliably able to detect a healthy loan, and classify it as such, 99% of the       time. At risk loans can be reliably detected and classified correctly 91% of the time.
    * F1
      The model supports precision and recall are balanced and can reliably recognize healhty loans 100% of the       time, and at-risk loans 88% of the time while minimizing false negative, and false positive values. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
* Regarding high-risk loans, the model is able to predict which loans were approaching default with 85% precision. Ability of the model to correctly identify a loan as high-risk, is 91%. This may be due to only 3% of the data being labeled as high-risk, putting the model at a disadvantage as to how a high-risk loan is defined for training. Regarding healthy loans, the data show that the model has a 100% precision rate for predicting healthy loans, while correctly identifying healthy loans 99% of the time.
