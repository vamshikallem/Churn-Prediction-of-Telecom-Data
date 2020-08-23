# Churn-Prediction-of-Telecom-Data
This project is focused on end to end application of Machine Learning methodologies to achieve best predicting accuracy. Our goal is to predict churn rate of customers 
for a telecom service provider based on service charges and usage data of customer.

The dataset which will be used for this project is Telecom data which comprises of 6999 entries and 21 columns which describe the various factors that affect churn and 
churn column would be my target variable. It is available in Kaggle. 21 columns of dataset are, State, account length, area code, phone number, international plan,
voice mail plan, number of voicemail messages, total day minutes, total day calls, day charge, evening minutes, eve calls, evening charge, night minutes, night charge,
international minutes, international calls, international charge, customer service calls, churn etc.

SOURCE: https://www.kaggle.com/becksddf/churn-in-telecoms-dataset

Our goal is to predict customers who are most likely to churn or change telecom networks. As it turns out to be a classification problem, I am using Logistic Regression
from regression algorithms, K-Nearest Neighbors to learn how Nearest-Neighbors would work on this dataset and Random forest algorithms from decision trees family to perform
classification analysis on data to predict churn.

To overcome the problem of overfitting I have applied PCA and also clustered the categorical columns to avoid information loss from those columns.

To improve the model and to perform hyper parameter tuning, I have successfully applied Ensemble method (Bagging) and Grid Search.
From my analysis, I have observed that Random Forest Classifier is best model fit to the data set being an ensemble method it gave better results. Though I have applied
Bagging, Grid Search, the accuracy has increased only by 2% even after lot of hard work.

But after performing Random Forest on data which is Clustered and applied PCA gives an accuray of 97% on test data which is 2% more than just Random Forest classifier. 
