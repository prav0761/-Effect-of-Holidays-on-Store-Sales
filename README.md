Walmart Sales Bayesian Inference


This repository contains a code implementation of Bayesian inference to predict sales of Walmart stores. The code is written in Python and uses PyMC3 library for the implementation of Bayesian models.

Dependencies
The following dependencies are required to run the code:

PyMC3
Numpy
Pandas


File descriptions
walmart_sales.ipynb: Jupyter Notebook containing the code implementation of Bayesian inference for Walmart sales prediction.
train.csv: Data file containing the training data for Walmart sales prediction.
test.csv: Data file containing the test data for evaluating the performance of the model.


Usage
To run the code, open the Jupyter Notebook walmart_sales.ipynb and run the cells in the order they appear. The code will perform the following steps:

Load the training and test data.

Preprocess the data for missing values, outliers and convert variables to appropriate data types.
Train a Bayesian linear regression model using PyMC3.
Make predictions on the test data and evaluate the performance of the model using mean absolute error.

