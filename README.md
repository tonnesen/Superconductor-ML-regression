# Superconductor-ML-regression
This is a repository for our PHYS 448 final project which is to employ regression techniques for predicting critical superconducting temperatures.

The dataset we are using comes from https://www.kaggle.com/datasets/tunguz/superconductivty-data-data-set. 
Kam Hamidieh used this same data in his paper _A Data-Driven Statistical Model for Predicting the Critical Temperature of a Superconductor_ with an XGBoost algorithm, and we will be comparing our results to this.

There are 3 main files which correspond to the three different methods used for modeling and prediction: Gradient Trees, Lasso Regression, and Elastic Net Regression.

Of these, the Gradient Trees method seems to perform the best with results that match Hamidieh's. The regression models performed decently, but require many engineered featured which likely are overfitting the data.
