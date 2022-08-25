<img src="https://www.linformatique.org/wp-content/uploads/2021/04/walmart-logo.jpg" alt="WALMART LOGO" />

# Walmart : predict weekly sales

## Project 🚧

Name : Iandro Rakotondrandria

email : iandro.rak@gmail.com

Data : Data files are in "src" folder

Vidyard video : https://share.vidyard.com/watch/nfSTG7MPYBxLGb4F2BU7pM?

## Context 📇

Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores from the United States, headquartered in Bentonville, Arkansas. The company was founded by Sam Walton in 1962.

Walmart's marketing service has asked for a machine learning model able to estimate the weekly sales in their stores, with the best precision possible on the predictions made. Such a model would help them understand better how the sales are influenced by economic indicators, and might be used to plan future marketing campaigns.

For this project, we worked with a dataset that contains information about weekly sales achieved by different Walmart stores, and other variables such as the unemployment rate or the fuel price, that might be useful for predicting the amount of sales.

## Goals 🎯

The project can be divided into three steps:

- Part 1 : make an EDA and all the necessary preprocessings to prepare data for machine learning
- Part 2 : train a **linear regression model** (baseline)
- Part 3 : avoid overfitting by training a **regularized regression model**

## Deliverable 📬

To complete this project, we : 

- Created some visualizations
- Trained at least one **linear regression model** on the dataset, that predicts the amount of weekly sales as a function of the other variables
- Assessed the performances of the model by using a metric that is relevant for regression problems
- Interpreted the coefficients of the model to identify what features are important for the prediction
- Trained 2 models with **regularization (Lasso or Ridge)** to reduce overfitting
