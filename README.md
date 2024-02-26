# module_12_assignment

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
For the 0 (healthy loan) label:
Precision: 1.00
 Recall: 0.99
Specificity: 0.91
F1 Score: 1.00
For the 1 (high-risk loan) label:
Precision: 0.85
Recall: 0.91
Specificity: 0.99
F1 Score: 0.88


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
For the 0 (healthy loan) label:
Precision: 1.00
Recall: 0.99
Specificity: 0.99
F1 Score: 1.00

For the 1 (high-risk loan) label:
Precision: 0.84
Recall: 0.99
Specificity: 0.99
F1 Score: 0.91


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? The model that performs the best is ther Oversampled model. For the healthy loans, the oversampled model improved specificity. The Oversampled model also improved recall and F1 for the high-risk loans, while precision did lower, it still is reasonable.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
