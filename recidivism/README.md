# Understanding recidivism: a logistic regression model for clasifying new offenses
## #Legal #Scikit-learn 

This jupyter notebook aims at predicting the type of "new offenses" committed by offenders based on categorical features such as their previous offense, 
the type of release (parole, parole to detainer, etc), and demographical features of the offender (age, sex, race/ethnicity, etc) in Iowa, USA. 

Python and Scikit-Learn were used for this project. As part of exploratory data analysis, the association of categorical features was calculated with Cramer V. 
Logistic Regression, Decision Tree and Random Forest models were explored. Hyperparameter tuning was performed and the F1 Scores of the models were estimated
in order to compare the best model. Logistic Regression model proved to have the best performance.
