# Industrial_Copper_Modeling
Introduction
This project focuses on leveraging machine learning techniques to predict the selling price and status of industrial copper. By utilizing regression and classification models, along with data preprocessing and feature engineering, we aim to provide insights into pricing trends and transaction outcomes within the copper industry
Domain 
The domain of this project is manufacturing, specifically centered around the industrial application of copper materials.
Packages and Libraries
Make sure to install the following packages before running the code:
!pip install numpy
!pip install pandas
!pip install scikit-learn
!pip install xgboost
!pip install matplotlib
!pip install seaborn
!pip install streamlit

Overview
Data Preprocessing
Loaded Data: The initial step involved loading the copper dataset from a CSV file into a Pandas DataFrame.

Data Cleaning: Addressed missing values, outliers, and adjusted data types to ensure data integrity and consistency.

Handling Skewness: Applied transformations to handle skewed data distributions for improved model performance.

Feature Engineering
Correlation Analysis: Analyzed feature correlations to identify potential multicollinearity issues and optimize feature selection.
Modeling
Regression Model: Developed a Random Forest regression model to predict selling prices of copper based on various features.

Classification Model: Implemented an Extra Trees classification model to predict transaction status (e.g., Won, Lost, Draft).

Hyperparameter Optimization: Fine-tuned model parameters using techniques like GridSearchCV to enhance predictive accuracy.

Model Deployment: Serialized trained models using Pickle for deployment and future use.

Streamlit Application
User Interface: Created an interactive Streamlit web application allowing users to input data and obtain real-time predictions.

Functionality: Integrated the trained models into the Streamlit app to predict selling prices and transaction statuses based on user-provided inputs.

Technology and Skills 
Python
Numpy
Pandas
Scikit-Learn
Pickle
Streamlit


