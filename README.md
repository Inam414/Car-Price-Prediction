# Car Price Prediction Project

This project aims to predict the selling price of cars using various machine learning techniques. The primary model used in this project is XGBoost Regressor, with performance evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Overview

The project involves the following steps:

1. **Data Preprocessing**: 
    - Loading the dataset.
    - Checking for missing values and basic information.
    - Encoding categorical features.
    - Creating new features such as car age.
    - Handling missing values and outliers.
    - Scaling numeric features.

2. **Feature Engineering**:
    - Encoding categorical features using `LabelEncoder`.
    - Creating a new feature: `car_age` by subtracting the year of the car from the current year.
    - Scaling numeric features using `StandardScaler`.

3. **Model Training and Evaluation**:
    - Splitting the data into training and testing sets.
    - Training the XGBoost Regressor model with hyperparameter tuning.
    - Evaluating the model using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
    - Performing cross-validation to ensure the model's robustness.
    - Analyzing feature importance.

The primary model used in this project is XGBoost Regressor, which was selected for its efficiency and performance. The model's effectiveness is measured using MAE and RMSE metrics.

