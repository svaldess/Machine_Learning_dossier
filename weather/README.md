
This notebook explores the possibility of predicting the temperature in a given day based on numerical features such as precipitation, 
humidity, wind speed, among others. Scikit-Learn was used for processing and analyzing the data. The data was extracted from this [dataset](https://www.kaggle.com/budincsevity/szeged-weather).

As part of the project, first, the data was preprocessed and correlations were explored. A training, validation and test set were created. 
Due their very low percentage, missing values were dropped. Finally, all numerical data was standardize and all categorical data were one-hot encoded.

First a simple linear regression (without regularization) was performed. Afterwards, based on grid search, different models with different regularization 
(L1, L2 and Elastic Net) were carried out in order to compared their negative mean squared error. All models with regularization perform better than a simple regression model without regularization. 
Also, Elastic Net has seemed to have the smallest negative mean squared error.
