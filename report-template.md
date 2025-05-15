# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. To do this, I split the data into training and testing sets using DataFrames and the train_test_split function. Then, I created a logistic regression model with the original data using DataFrames, train_test_split, and the LogisticRegression functions. Lastly, I created the model.predict, confusion_matrix, and classification_report to view the predictions of the data for healthy and high-risk loans, as well as the accuracy of each prediction.

## Results

* Healthy Loan Predictions
    * Precision: 1.00
    * Recall: 0.99
    * F1-Score: 1.00
    * Support: 18,765

* High-Risk Loan Predictions
    * Precision: 0.84 
    * Recall: 0.94
    * F1-Score: 0.89
    * Support: 619

## Summary

The healthy loan predictions had higher precision and recall percentages, making them more accurate. However, they were slightly lower for high-risk loan predictions. This could be due to there being an imbalance in the data, with there being much less support instances for high-risk loans than for healthy loans. I would recommend referencing the F1-Scores, as they take both precision and recall into account to make more informed predictions.