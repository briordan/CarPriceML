# CarPriceML Using Ridge Regression to predict a car price based on features

## Overview
Using data from Kaggle to predict a car price based on features; and find the features that most 
heavily influence the price.

Cleaned up the data by dropping records that were missing data.  Used one hot encoding for categorical data 
that was encoded as text (and dropped one category to minimize colinearity errors).

Trained the model on 80% of the data and used the remaining 20% to predict the price.  

## Results
The training results R-squared is a 0.8968 which is a pretty close fit for the model.  The test results R-squared is
0.8722.  The largest factors affecting price positively were a rear engine, 8 cylinders, and the car being a convertible.
The largest factors affecting price negatively were a four cylinder engine, a wagon body style, and front wheel drive.  

Based on the data model coefficients it appears a number of features could be eliminated from the model to simplify it
with minimal impact on the model's accuracy.  

![Image of Predict Plot](https://github.com/briordan/CarPriceML/blob/master/CarPrices.jpg)
