# credit-risk-classification
Overview:
The primary aim of this analysis is to forecast the likelihood of loan default for individuals applying for loans. It factors in elements like loan size, interest rate, borrower's income, debt-to-income ratio, and total existing debt. Our objective was to predict whether an individual would be categorized as a safe borrower or not. Initially, we segregated the 'loan_status' variable from the larger dataset and then randomly divided the data into training and testing subsets. We subsequently applied a logistic regression model to the data to get accuracy metrics. Afterward, we experimented with data oversampling to see if it could yield a more accurate prediction using an augmented, synthetic dataset.

Results:
  Logistic Regression Model:
  Accuracy: 0.99
  Precision for Healthy Loans: 1.00
  Recall for Healthy Loans: 0.99
  Precision for High-Risk Loans: 0.85
  Recall for High-Risk Loans: 0.91

  RandomOverSampler:
  Accuracy: 0.99
  Precision for Healthy Loans: 0.99
  Recall for Healthy Loans: 0.99
  Precision for High-Risk Loans: 0.99
  Recall for High-Risk Loans: 0.99

Summary:
In my personal assessment, the Logistic Regression model applied to the original data appears to be the more reliable choice due to the overfitting of the second model.
