# Report

## Overview of the Analysis

* This project involves building the logistic regression machine learning model to classify credit risk. The goal is to predict whether a loan applicant poses a high or low credit risk based on their income, dept, and other relevant factors.
* The financial data that was recorded includes: 
    * `loan_size` 
    * `interest_rate`
    * `borrower_income`
    * `total_debt`
    * `debt_to_income` ratio
    * `num_of_accounts`
    * `derogatory_marks`
    * `loan_status`
* The variable we are trying to predict the `loan_status`, based on other data provided.
* Here is the process that was used to predict the data:
    1. Created labels (X and y). We set the y label as the `loan_status` column of the data, while the X label is the rest of the data.
    2. We randomly split the data into training and testing data using the `train_test_split` method from sklearn.
    3. A logistic regression model was created and was fitted and trained with the data.
    4. Predictions were saved and the model was evaluated for performance
* The machine learning model used was `Logistic Regression`. No other machine learning models were used.

## Results

Here are the results:

* Accuracy:     0.99
* Precision:    (Prediction 0: 1.00, Prediction 1: 0.84)
* Recall:       (Prediction 0: 0.99, Prediction 1: 0.94)

## Summary

The logistic regression model performed very well in predicting credit risk. With an accuracy of 0.99, the model is very reliable. The precision scores indicate that the model is very precise at predicting low credit risk (Prediction 0: 1.00) and pretty precise at predicting high credit risk (Prediction 1: 0.84). The recall scores indicate the model is great at identifying low credit risk situations (Prediction 0: 0.99) and also does good at identifying high credit risk cases (Prediction 1: 0.94). Overall, the model demonstrates good performance in both precision and recall, making it a great tool for credit risk classification.

I would use this particular model in this situation because it did very well in the testing phase, with an overall accuracy score of 99%.