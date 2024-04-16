# Credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this activity is to train and evaluate machine learning models based on loan risk. 

* Explain what financial information the data was on, and what you needed to predict.
The target financial information in the data is the loan status and we needed to predict the loan status based on the loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts,  derogatory_marks and total_debt. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The dataset contained 77535 rows of values that was split into 2 which was called training and testing datasets. I used logistic regression module to help us determine whether a borrower would be a low or high risk. 

* Describe the stages of the machine learning process you went through as part of this analysis.
* Step 1: Read the `lending_data.csv` data from the `Resources` folder into a Pandas DataFrame.
* Step 2: Create the labels set (`y`)  from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.
* Step 3: Split the data into training and testing datasets by using `train_test_split`.
* Step 4: Create a Logistic Regression Model with the Original Data
    a. Step 1: Fit a logistic regression model by using the training data (`X_train` and `y_train`).
    b. Step 2: Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
    c. Step 3: Evaluate the model’s performance by doing the following:
        a(i) Generate a confusion matrix.
        b(i) Print the classification report.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithm).
* We used LogisticRegression.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
