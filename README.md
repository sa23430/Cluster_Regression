# Clusterwise Linear Regression using Flexmix

This  provides information regarding clustering using R-package Flexmix. Flexmix implements a general framework for finite mixtures of regression models using the EM algorithm. Flexmix provides  the E-step and all data handling, while the M-step can be supplied by the user to easily define new models. This algorithm implements mixtures of standard linear models, generalized linear models and model based clustering. 

## Use of Generalized clusterwise linear regression
when: we have access to limited number of predictors.      know other predictors would be useful but don't have access to them OR know other predictors would be useful but they are highly correlated.     assume the data set could be clustered efficiently based on those other predictors

## Mall_customer_shopping notebook
  This used Flexmix to cluster customers in to 2 or 3 segments based on their Age, Gender and Income bracket. Regression modelling is then performed to predict spending score of that particular cluster.
  
  
## cluster_regression notebook
I implemented cluster regression algorithm in Python and tested it out using German Credit and Cars datasets!

  
