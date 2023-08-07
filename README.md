# credit-risk-classification Report 

## Overview of the Analysis

The purpose of this analysis was to evaluate potential loan applicants to identify whether they are high-risk or low-risk borrowers. The primary objective was to build a machine learning model that can predict the risk associated with a particular loan based on various financial features.

The data used in this analysis consisted of several factors such as loan size, interest rate, borrower income, debt to income ratio, number of credit accounts, derogatory marks, and total debt. Our main target variable was the 'loan_status', which we needed to predict. It is a binary variable with '1' indicating a 'High-Risk' loan and '0' signifying a 'Healthy' loan.

The stages of the machine learning process for this analysis included splitting the data into training and testing sets, fitting the data to the Logistic Regression model, and making predictions using the testing data. We also generated a confusion matrix to visualize the performance of the model, calculated accuracy scores, and used the classification report to get detailed precision and recall scores.

## Results

For the Logistic Regression model, the results were as follows:

* Logistic Regression Model:
  * Accuracy Score: The accuracy of the model on both the training and testing data was 99.2%, indicating that the model was able to correctly predict the loan status 99.2% of the time.
  * Precision Score: For the 'Healthy' loan status, the precision was 1.00, meaning when the model predicted a loan to be 'Healthy', it was correct 100% of the time. The precision for the 'High-risk' loan status was 0.85, indicating an 85% correctness when the model predicted a loan to be 'High-risk'.
  * Recall Score: The recall for 'Healthy' loans was 0.99, showing that the model correctly identified 99% of the actual 'Healthy' loans. For 'High-risk' loans, the recall was 0.91, which means the model correctly identified 91% of the actual 'High-risk' loans.

## Summary

The logistic regression model performed exceptionally well at predicting both 'Healthy' and 'High-risk' loan statuses. The model displayed high accuracy, precision, and recall scores. 

Given the results, the logistic regression model seems to perform best due to its high accuracy, precision, and recall scores. We can say it performs the best because it has a high ability to predict both 'Healthy' and 'High-risk' loans correctly. The performance does depend on the problem we're trying to solve - in this case, we are interested in correctly predicting both 'Healthy' and 'High-risk' loans, and this model does an excellent job at both.

I would recommend using the logistic regression model due to its impressive performance in this scenario. However, it is essential to remember that we should still continue to validate the model with new data, and the results might change as the nature of the data changes.