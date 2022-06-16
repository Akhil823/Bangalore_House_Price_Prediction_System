# Bangalore_House_Price_Prediction_System

This project is to predict the price of a house in Bangalore.

First, I have performed data cleaning such as handling null values, outlier removal. I have also performed dimensionality reduction.

Then, used one hot encoding to encode names of different locations. 

For model selection I have used pycaret to know which model gives us the best result. The best result was obtained from bayesian ridge (as given by pycaret). Hence, at last I applied Bayesian Ridge Regression to predict price of a house in Bangalore based on location, BHK and bathroom.
