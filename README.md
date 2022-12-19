# Bangalore_House_Price_Prediction_System

This project is to predict the price of a house in Bangalore.

First, I have performed data cleaning such as handling null values, outlier removal. I have also performed dimensionality reduction.

Then, used one hot encoding to encode names of different locations. 

For model selection I have used pycaret to know which model gives us the best result. The best result was obtained from ridge regression (as given by pycaret). Hence, at last I applied Ridge Regression to predict price of a house in Bangalore based on location, BHK and bathroom.


# Dataset

![image](https://user-images.githubusercontent.com/57368125/208423755-0ee29818-98c6-4de0-9800-703add86162e.png)


# Data Cleaning
<ul>
  <li> Dropping the columns which are not required </li>
  <li> Deleting the rows with null enteries</li>
  <li> Data Normalization</li>
  <li> Outlier Removal </li>
  <li> One Hot Encoding </li>
 </ul>
 
 # Comparing models using PyCaret
 ![image](https://user-images.githubusercontent.com/57368125/208424581-6803d82f-9f59-45ad-8297-ce012f27c065.png)
