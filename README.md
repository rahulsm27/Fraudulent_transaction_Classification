# Credit transaction Project using classical ML algorithms

## Business Problem
- To build a Machine learning model capable of identifying credit card transaction as fraudulent or not in real time as they are being made so that it helps business and customers avoid unnecessary wastage of money and time.

- The dataset is highly imbalanced
Data can be found @ https://www.kaggle.com/mlg-ulb/creditcardfraud

## Solution

1. Build a credit transaction analysis model using classical ml algorithms

2.	Understanding the data: Make sense of various variables available to us. Identify dependent and independent variables.

3.	EDA: Perform univariate/bivariate analysis. Check for feature transformations/engineering. Check for distribution, skewness and imbalance of target variable. Apply appropriate technique to resolve if required. 


4. Performed class balancing techniques with :
- Random Oversampling
- SMOTE
- ADASYN

5. Apply various ML algorithms like 
- LogisticRegression 
- KNN
- DecistionTree 
- RandomForest
- XGBoost 

using grid search cv to find the best model with the best parameters to classify the transaction of a credit card company to detect fraudulent transactions

6.	EVALUATE: Freeze on final model. Evaluate the model on test data. 

7.	CONCULDE: Identify variables important for prediction. 
