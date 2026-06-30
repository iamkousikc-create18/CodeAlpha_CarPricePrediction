# Car Price Prediction

## Overview

This project is part of the **CodeAlpha Data Science Internship**. The objective is to develop a machine learning model that predicts the selling price of a used car based on its features. The project includes data preprocessing, exploratory data analysis, model training, and performance evaluation.

## Objective

The objective of this project is to build a machine learning regression model that accurately predicts the selling price of used cars using vehicle attributes and market-related features.

## Dataset

The dataset contains information about used cars, including their specifications and selling prices.

### Features

* Car Name
* Year
* Present Price
* Kms Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

### Target Variable

* Selling Price

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

1. Load and explore the dataset.
2. Perform data preprocessing and feature engineering.
3. Conduct exploratory data analysis (EDA).
4. Split the dataset into training and testing sets.
5. Train Linear Regression, Ridge Regression, and Lasso Regression models.
6. Evaluate model performance using R² Score, MAE, MSE, and RMSE.
7. Compare model performance and select the best-performing model.

## Results

* Successfully predicted used car selling prices using machine learning.
* Compared multiple regression models for performance evaluation.
* Linear Regression achieved the best performance with an **R² Score of 0.8467**.

## Key Insights

* Present Price is the strongest predictor of Selling Price.
* Vehicle characteristics such as Year, Fuel Type, Transmission, and Kilometers Driven significantly influence resale value.
* Linear Regression slightly outperformed Ridge and Lasso Regression on this dataset.
* The trained model provides reliable predictions for estimating used car prices.

## Conclusion

This project demonstrates how machine learning regression techniques can be applied to estimate used car prices. The developed model achieved strong predictive performance and can support data-driven pricing decisions.

## Repository Structure

├── Task 3.ipynb

├── car data.csv

├── README.md

└── requirements.txt

## Author

**Kousik Chakraborty**

**CodeAlpha Data Science Internship**
