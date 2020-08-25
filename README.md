# Machine Learning Projects

This repo has some of my Machine Learning projects, including:

## Understanding recidivism: a logistic regression model for clasifying new offenses
This notebook explores how prediction new offenses committed by offenders based on categorical features such as their previous offense, the type of release (parole, parole to detainer, etc),
and demographical features of the offender (age, sex, race/ethnicity, etc) in Iowa, USA. **Scikit-Learn** was used for this project. Logistic Regression, Decision Tree and Random Forest models were explored. Hyperparameter tuning was performed and the F1 Scores of the models were estimated. 

## Analysis of credit card patterns: K-Means Clustering and linear Regression Model
This notebook identifies clusters of credit card users, using **K-means clustering** and **Principal Components Analysis**. Then, using a **Linear Regression Model with Ridge regularization**, the amount of payments done by the users is predicted based on features such as balance of their account, how frequently the balance is updated, amount of purchases on the account, cash in advance given by the user, credit card limit, among other features. **Scikit-Learn** was used for this project.

## Predicting temperature with a linear regression model 
This notebook explores the possibility of predicting the temperature in a given day based on numerical features such as precipitation, humidity, wind speed, among others. Hyperparameter tuning is used to compare the prediction given by regression models with different types regularization: Lasso, Ridge and Elastic Net. 
**Scikit-Learn** was used for this project.
