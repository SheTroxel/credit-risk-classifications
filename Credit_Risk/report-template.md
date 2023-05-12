# Credit Risk Analysis

## Overview of the Analysis

To minimize credit risk to the overall loan portfolio for a peer-to-peer lending services company, historical lending activity data was evaluated to develop a machine learning model that could accurately identify the creditworthiness of borrowers. The historical data included a loan status column which identified which loans were healthy (1) and which loans had defaulted (0). 

To create a model that can accurately identify the creditworthiness of borrows, the historical lending data was imported into a pandas DataFrame. From the DataFrame, the "loan_status" was select for the label set (`y`) and for the features set (`X`), the remaining columns of data were used. Once the label and feature sets were identified, the data was split into Training and Testing sets. Training sets are used to train the model in determining if a loan is healthy(1) or not (0). The testing sets are used to ensure that all new data coming into the model is evaluated acurrately.

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



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
