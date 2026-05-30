# House Price Prediction using Linear Regression

This notebook demonstrates a basic machine learning workflow to predict house prices using a Linear Regression model. It leverages two datasets: a general housing dataset (from Hands-On Machine Learning) for initial exploration and the Ames Housing dataset (Kaggle's House Prices - Advanced Regression Techniques competition) for the primary prediction task.

## Project Overview

The goal of this project is to build and evaluate a simple linear regression model to predict the sale price of houses based on various features. The process includes:

1.  **Data Acquisition**: Downloading and extracting the necessary datasets.
2.  **Data Loading and Initial Exploration**: Loading the datasets into pandas DataFrames and performing initial checks (head, info).
3.  **Exploratory Data Analysis (EDA)**: Visualizing relationships between key features (e.g., living area vs. sale price).
4.  **Feature Engineering**: Creating new features to improve model performance (e.g., `TotalBaths`).
5.  **Model Training**: Training a Linear Regression model.
6.  **Model Evaluation**: Assessing model performance using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared. This also includes visualizing actual vs. predicted values.
7.  **Feature Improvement & Cross-Validation**: Iteratively improving the model by adding more relevant features and using K-Fold Cross-Validation for robust evaluation.

## Dataset

This project uses two datasets:

*   **Housing Dataset (Ageron's Hands-On ML)**: Used for initial demonstration of data loading (`housing.csv`).
*   **Ames Housing Dataset**: The primary dataset for house price prediction. It contains detailed information about residential homes in Ames, Iowa, and their sale prices (`train.csv` from `house-prices-advanced-regression-techniques.zip`).

## Setup and Installation

To run this notebook, you'll need the following libraries:

*   `requests`
*   `pandas`
*   `matplotlib`
*   `seaborn`
*   `scikit-learn`
*   `numpy`
