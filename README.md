#  House Price Prediction

## Overview

This project focuses on predicting residential house prices using supervised Machine Learning regression techniques. It explores the relationship between property characteristics and their corresponding prices to develop predictive models.

Two regression algorithms, Multiple Linear Regression and Random Forest Regression, are implemented and evaluated to compare their predictive performance.

## Objectives

- Analyze housing data to identify factors influencing house prices.
- Apply data preprocessing and feature encoding techniques.
- Build regression models for house price prediction.
- Optimize Random Forest hyperparameters using GridSearchCV.
- Evaluate and compare model performance using standard regression metrics.

##  Machine Learning Algorithms

**1. Multiple Linear Regression**
- Establishes linear relationships between input features and house prices.
- Uses StandardScaler for feature scaling.
- Serves as a baseline regression model.

**2. Random Forest Regression**
- Uses an ensemble of decision trees to capture complex relationships.
- Handles nonlinear patterns in housing data.
- Applies GridSearchCV for hyperparameter optimization.

##  Methodology

1. **Data Preprocessing**
   - Handle categorical features using binary encoding and one-hot encoding.
   - Separate input features and target variable.

2. **Data Splitting**
   - 80:20 train-test split.
   - `random_state=42` for reproducibility.

3. **Feature Scaling**
   - Apply StandardScaler to Multiple Linear Regression.
   - Use unscaled features for Random Forest Regression.

4. **Model Training**
   - Train Multiple Linear Regression with default parameters.
   - Train Random Forest Regression with `n_estimators=200`.

5. **Hyperparameter Tuning**
   - Apply GridSearchCV to optimize Random Forest parameters.
   - Use 5-fold cross-validation.

6. **Model Evaluation**
   - Evaluate both models on the test dataset.

##  Evaluation
R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

##  Technologies & Libraries

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Model Optimization:** GridSearchCV


## Project Links
Kaggle Notebook: https://www.kaggle.com/code/mafruda/house-price-prediction

GitHub Repository: https://github.com/Mafruda14/HousePricePrediction
