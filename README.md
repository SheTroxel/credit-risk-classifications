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

Once the data was review, I split the data into training and testing datasets by using `train_test_split`.

### Create a Logistic Regression Model with the Original Data
Next, I fit a logistic regression model by using the training data (`X-train` and `y_train`). I saved the predictions for the testing data lables by using the testing feature data(`X_test`) and the fitted model.
I then evaluated the model's prefromance by doing the following:

 * Calcuated the accuracy score of the model. 
 
 The accuracy score of this model: 0.9924164259182832 or 99%. 
 
 A balance score report was also calculated. The balance score of this model: 0.9442676901753825 or 94%.
 
 * Generated a confusion matrix which resulted in the following array:
 
 `array ([18679,    67],
         [80,   558]], dtype=int64)'
 
 * Printed the classification report
 
 ![ModelOne_Image](Credit_Risk/Creditmodel_one_report.JPG)

