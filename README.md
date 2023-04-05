# Car-Price-Predict

This project predicting car's selling price as using year of car, present price, km, fuel type, seller type, transmission and owner parameters.

In this project Linear Regression model used. For improving model  I used Polynomial Features library. Projects train accuracy is %88 and cross validation accuracy is %81. With using polynomial features model improved to %99 train accuracy and %92 cross validation accuracy.

Project's MSES
Non-poly Train MSE: 1.39
Non-poly CV MSE: 1.02

Polynomial Train MSE: 0.11
Polynomial CV MSE: 0.43

Libraries required for the project:
Numpy
pandas
os
matplotlib.pyplot
Seaborn
sklearn.linear_model import LinearRegression
sklearn.metrics
sklearn.model_selection

This project worked on Google Colaboratory. Data's directory should be changed.
