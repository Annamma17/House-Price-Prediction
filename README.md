# House-Price-Prediction-
This repository consists of various approaches of house price prediction analysis.
1. 'HousePrice_linear_ridege.ipynb' predicts the pricing of some houses based on linear regression and ridge regression : 
* It makes use of libraries such as NumPy, pandas, seaborn, statsmodels, sklearn.
* It treats outliers, skewness, and missing terms.
* Unnecessary data are replaced using the 'dummies' and some which provide no relevant information are removed.
* Linear regression is carried out by both statsmodels and sklearn.
* Data is further splited as train and test data and then preprocessed.
* Ridge regression is then implemented on the data.
* r square value obtained after linear regression = 0.712
* r square value obtained after ridge regression = 0.7564
* Inference : Ridge regression improved the accuracy of the model than the one obtained after linear regression!
