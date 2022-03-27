# Module 12 Report

## Overview of the Analysis

This notebook use machine learning algorithms to predict the loan status. In other words the model detects the high-risk loans.

* The data provided consist of 7 dimensions with 8 k loans. Also the data when counted and plotted it was determine that it was an imbalance class, so the appropriate modifications to the model was need it to be done to take into consideration.

* The high-level overview of the process is as follow: first the data must be clean and scale in order to split it into the training and the testing data. After the fact we use a logistic regression model to predict if a loan is high-risk or not, from the data provided like loan size, interest rate, borrower income, etc.


## Results

Below you will read the results of two models predicting the same data, the only difference is the imbalance optimization technic to get better results.

* Machine Learning Model 1:
  * Model 1 has a precision of 100% with the no risky loans and an 85% with the high-risk loans. We can see in the results that both have a 90% + in the recall parameter with an accuracy of 95%.



* Machine Learning Model 2:
  * Model 2 has a precision of 100% with the no risky loans and an 84% with the high-risk loans. We can see in the results that both have a 99% in the recall parameter with an accuracy of 99%.

## Summary

After analyzing the results, we can see that model 2 is clearly more accurate and precise with a better recall. So, in my opinion it is the best model to go with. In this specific case I believe we need to have a better recall and accuracy since we want to correctly predict the high-risk loans, o I recommend using the second model.
