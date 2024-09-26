# Credit Card Routing Model

This repository contains a predictive modeling project for optimizing credit card payment routing based on success rates and transaction fees. The model uses logistic regression to predict the best payment service provider (PSP) for each transaction, improving success rates and lowering fees.

## Project Overview
- **Objective**: Automate credit card routing to increase payment success rates and minimize transaction fees.
- **Methodology**: 
  - Data cleaning
  - Feature engineering
  - Logistic regression model with cross-validation
  - Confusion matrix for evaluating model performance

## Features
- **Amount**: Transaction amount
- **Country**: Country of the transaction
- **PSP**: Payment Service Provider (e.g., Moneycard, Goldcard)
- **Success**: Whether the payment was successful or not

## Installation
To run the code, install the following dependencies:

pip install pandas numpy scikit-learn seaborn matplotlib