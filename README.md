# Credit-risk-classifications Challenge
Using historical lending activity from a peer-to-peer lending services company, this challenged required me to build a model that can identify the creditworthiness of borrowers.
The instructions for this challenge are divided into the following subsections:
  * Split the Data into Training and Testing Sets

  * Create a Logistic Regression Model with the Original Data

  * Predict a Logistic Regression Model with Resampled Training Data

  * Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets
To begin the challenge, I read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame.
Created the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
  
  * A value of 0 in the "loan_status" column indicates that a loan is healthy. 
  
  * A value of 1 in the "loan_status" column indicates that a loan has a high risk of default.
