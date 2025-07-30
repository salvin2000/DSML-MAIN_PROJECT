Credit Card Default Prediction
This is my machine learning project to predict if a credit card customer will default on their payment in the next month. The dataset includes customer demographics and financial data—my goal was to build and compare classification models for this binary prediction task.

Project Overview
I started by cleaning the data, especially handling rare/unknown values in the EDUCATION and MARRIAGE columns. I also dropped the ID column since it’s not useful for prediction. After that, I did some exploratory data analysis to check feature distributions, correlations, and spot any issues or outliers.

Dataset
The main features are things like:

LIMIT_BAL (Credit limit)

SEX, EDUCATION, MARRIAGE, and AGE

Payment status: PAY_0, PAY_2, ..., PAY_6

Past bill amounts: BILL_AMT1 ... BILL_AMT6

Previous payments: PAY_AMT1 ... PAY_AMT6

Target: default payment next month 

Steps I Followed,
Cleaned data and regrouped rare/unknown categories.

Did one hot encoding using get_dummies()

Splited and trained the data using train test split
