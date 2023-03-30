# Build-a-model-to-estimate-the-price-of-a-house
## Multi-Variable Regression with Regression Trees
Multi-Variable Regression with Regression Trees
This project demonstrates how to build a regression model to estimate the price of a house based on features of the house and the neighborhood. The Boston dataset from the sklearn library is used as an example, and a regression tree algorithm is used to build the model.

## Overview
In this project, we explore how to build a regression model to estimate the price of a house based on various features such as number of rooms, crime rate, and accessibility to highways. We use the Boston dataset, which contains information on 506 houses in the Boston area. We build a regression tree algorithm to train the model and predict house prices.

## Installation
To use this project, you will need to have Python 3 installed, along with the following libraries:

pandas
numpy
sklearn

## You can install these libraries using pip:
pip install pandas numpy sklearn

## Usage
To use this project, simply download the repository and run the multi_variable_regression.py file. The script will load the Boston dataset, split it into training and test sets, train a regression tree model on the training set, and evaluate the performance of the model on the test set.

## Results
Our regression tree model achieves a mean absolute error of $2,835.86 on the test set, indicating that it is a relatively accurate estimator of house prices. We also visualize the regression tree to gain insights into the most important features for predicting house prices.
