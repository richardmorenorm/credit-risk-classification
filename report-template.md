# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers.
* The financial information was a historical lending activity from a peer-to-peer lending services company.
* For this analysis, the loan status was used as a dependant variable (y value) to determine if a loan was healthy or at risk.
* The data is split to traning and test sets. Then, dependent and independent variables are defined. Next, a logistic regression model is created and an original data is fitted to the model. The trained model is used to make predictions. Lastly, the model`s performance is evaluated.
* Two Logistic Regression models were ran using the original dataset and a resampled dataset.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    * Accuracy: 0.9520479254722232
    * Precision: .92 (Macro Avg), .99 (Weighted Avg)
    * Recall: .95 (Macro Avg), .99 (Weighted Avg)



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    * Accuracy: 0.9936781215845847
    * Precision: .92 (Macro Avg), .99 (Weighted Avg)
    * Recall: .99 (Macro Avg), .99 (Weighted Avg)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Randomly oversampling the data resulted in a higher balanced accuracy and recall score. With higher recall value, the resampled model predicted risky loans more accurately.
* While the 0s (healthy applicants) did reveal higher scores, it still important to pull data from the 1s (high risk applicants) since the model is being used to predict credit worthiness.

If you do not recommend any of the models, please justify your reasoning.
