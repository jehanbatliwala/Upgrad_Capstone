# **Prediction-of-Credit-Card-Fraud**-

UpGrad Final Capstone Project of Data Science
<br>
Author : Jehan Batliwala <br>
Email Id : jehan2898@gmail.com

# **About Projects**

This project is related to machine learning model, where we are able to make a model to detect whether the transaction is Legitimate or Fraud transaction based on the given input. So the goal of this project is to create a machine learning model that effectively identify the credit card fraud based on the data we input or have , and get the comparision of the model performance.

# **About the Datasets**

Credit Card is playing a vital role in current era, as per the concern of few data base in European Geography over 75% of polpulation having atleast one credit card. Such a great nuber show the how fraud risk have with the finanical institution and bank.

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

The data contain only numerical input variables, and that is nothing but a PCA(Principal Component Analysis) transformation because of confidentiality issues, we cannot provide the original features and more relatistic and clear information about the data. Features V1, V2, … V28 are the principal components obtained with PCA,
The only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning.
The Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 for Legitimate transanctions.

# Steps of creating model

1. Exploratory Data Analysis(EDA)
2. Data Preparation
3. Training and Testing data
4. Fit the Model
5. Evaluate the Model
6. Deployment

# List of Imported Libraries

1. Pandas
2. Numpy
3. Matplotlib.pyplot
4. Searborn
5. Scikit-Learn

# List of used Models

1. Logistic Regression Model
2. Random Forest Model
3. XGBoost Model
