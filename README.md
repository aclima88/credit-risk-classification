#credit-risk-classification

# Split the Data into Training and Testing Sets

1. Imported the needed modules
2. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
3.Created the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
4. Checked the balance of the labels variable (y) by using the value_counts function.
5. Split the data into training and testing datasets by using train_test_split.

# Create a Logistic Regression Model with the Original Data

6. Fit a logistic regression model by using the training data (X_train and y_train).
7. Saved the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
8. Evaluated the model’s performance by doing the following:
   a. Calculating the accuracy score of the model.
   b. Generating a confusion matrix.
   c. Printing the classification report.

![classification_report](https://github.com/aclima88/credit-risk-classification/assets/133547307/4e53358e-1b19-4f98-87bb-4ff8c4870936)


# Predict a Logistic Regression Model with Resampled Training Data

9. Used the RandomOverSampler module from the imbalanced-learn library to resample the data. Be sure to confirm that the labels have an equal number of data points.
10.Used the LogisticRegression classifier and the resampled data to fit the model and make predictions.
11. Evaluated the model’s performance by doing the following:
   a. Calculating the accuracy score of the model.
   b. Generating a confusion matrix.
   c. Printing the classification report.

![classification_report_resampled_data](https://github.com/aclima88/credit-risk-classification/assets/133547307/f4f09a50-d72a-42e0-9919-3d2c69f64cf1)
