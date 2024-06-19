
# Industrial Copper Modeling 

# Introduction

This project focuses on leveraging machine learning techniques to predict the selling price and status of industrial copper. By utilizing regression and classification models, along with data preprocessing and feature engineering, we aim to provide insights into pricing trends and transaction outcomes within the copper industry.
## Objective
Selling Price Prediction: 

Develop a regression model to forecast the selling price of copper based on various factors such as quantity, customer, country, and product specifications.

Transaction Status Prediction:

 Build a classification model to predict the status of copper transactions (e.g., Won, Lost, Draft) using historical data and transaction attributes.

Insight Generation:

 Extract meaningful insights into pricing trends, customer preferences, and transaction outcomes within the copper industry to inform strategic decision-making.

Model Deployment: 

Create a user-friendly web application using Streamlit to provide interactive predictions and facilitate real-time decision support for stakeholders in the manufacturing sector.
## Technology used
1. Python

2. Numpy

3. Pandas

4. Scikit-Learn

5. Pickle

6. Streamlit
## Overview
## Data Preprocessing
1.Loaded Data:

 The initial step involved loading the copper dataset from a CSV file into a Pandas DataFrame.

2.Data Cleaning:

 Addressed missing values, outliers, and adjusted data types to ensure data integrity and consistency.

3.Handling Skewness: 

Applied transformations to handle skewed data distributions for improved model performance.

## Feature Engineering
1.Correlation Analysis:

 Analyzed feature correlations to identify potential multicollinearity issues and optimize feature selection.
## Modeling

1.Regression Model:

 Developed a Random Forest regression model to predict selling prices of copper based on various features.

2.Classification Model: 

Implemented an Extra Trees classification model to predict transaction status (e.g., Won, Lost, Draft).

3.Hyperparameter Optimization:

Fine-tuned model parameters using techniques like GridSearchCV to enhance predictive accuracy.

4.Model Deployment: 

Serialized trained models using Pickle for deployment and future use.

## Streamlit Application

1.User Interface: 

Created an interactive Streamlit web application allowing users to input data and obtain real-time predictions.

2.Functionality: 

Integrated the trained models into the Streamlit app to predict selling prices and transaction statuses based on user-provided inputs.




## Packages
!pip install pandas

!pip install numpy

!pip install matplotlib

!pip install streamlit

!pip install scikit-learn

!pip install xgboost

!pip install seaborn


## Reference

1.Python Documentation

2.pandas Documentation

3.numpy Documentation

4.Streamlit Documentation

5.scikit-learn Documentation

