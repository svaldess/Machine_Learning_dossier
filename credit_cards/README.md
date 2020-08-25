# Analysis of credit card patterns: : K-Means Clustering and Linear Regression Model

This notebook identifies clusters of credit card users, using **K-means clustering**. **Principal Components Analysis (PCA)** is used to reduce 
the dimensionality of the data. Dividing the users in clusters is useful, first, to understand credit patterns and, second, to create better market strategies.

On a second part, I predict the amount of payments done by the users based on features such as balance of their account, 
how frequently the Balance is updated, amount of purchases on the account, cash in advance given by the user, 
credit card limit, among others. After performing hyperparameter tuing, **Linear Regression model** with Ridge regularization proved to be the best model. 
