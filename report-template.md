# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


## Personal Report

##Overview of the Analysis

The purpose of this analysis was to evaluate credit risk by predicting whether a loan was healthy or high-risk using logistic regression. A logistic regression model was trained on the training data, and predictions were made on the test set. The model's performance was evaluated using a confusion matrix and a classification report.

## Results

-Machine Learning Model 1:
-Accuracy: 0.99
-Precision (label 0): 1.00
-Recall (label 0): 0.99
-Precision (label 1): 0.85
-Recall (label 1): 0.95

## Summary

The logistic regression model performed very well, with an overall accuracy of 99%. It identified healthy loans with perfect precision and nearly perfect recall. It also did a strong job identifying high-risk loans, with high precision and even higher recall. Because this model performs reliably for both classes, and especially because it detects the majority of high-risk loans, it is recommended for use in predicting credit risk.