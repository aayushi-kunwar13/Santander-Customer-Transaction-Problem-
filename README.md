# Santander-Customer-Transaction-Problem-
Source: https://www.kaggle.com/c/santander-customer-transaction-prediction/overview

PROBLEM STATEMENT - 
identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted.
The data provided for this competition has the same structure as the real data we have available to solve this problem.

PROCESSING - 
1.explore the data.
2. prepare it for a model .
3. train a model.
4. predict the target value for the test set
5. then prepare a submission.

FEATURE ENGINEERING - 
Create simple features like sum, min, max, mean, std, skew, kurt and median and create some rounded features .

As a DATA AGUMENTATION STEP , performed data oversampling as the data is imbalanced.
Oversampling is used using imblearn library which makes copies of minority class by some fraction whereas using undersampling 
lead to loss of infromation and hence it reduces the accuracy due to lack of information.

MODEL USED - Light GBM Model with simple features.
Light GBM is a gradient boosting framework that uses tree based learning algorithm.
