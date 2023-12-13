# README for Macroeconomic Data Analysis and Regression Model

## Overview

This repository contains a Python script for performing exploratory data analysis (EDA), visualization, data preprocessing, regression modeling, and diagnostic testing on macroeconomic data. The script utilizes various statistical and machine learning techniques to understand the relationships between different macroeconomic variables and to build a regression model for predicting a specific dependent variable.

## Requirements

The script requires Python and the following libraries:

- pandas
- matplotlib
- seaborn
- numpy
- statsmodels
- scikit-learn
- scipy
- math
- warnings
- google.colab (for Google Colab integration)

## Data

The dataset used in this analysis is a collection of macroeconomic variables. The data is loaded from a CSV file hosted on Google Drive and is specifically designed for regression analysis.

## Features of the Script

1. **Google Colab Drive Mount**: Integration with Google Colab for data import.

2. **Exploratory Data Analysis (EDA)**: Basic data exploration including viewing the first few rows, understanding the data shape, descriptive statistics, and checking for missing values.

3. **Data Visualization**:
   - Histograms for each variable.
   - Boxplots for outlier detection.
   - Scatter plots to visualize relationships between predictor variables and the dependent variable.
   - Correlation matrix heat map.

4. **Data Preparation**:
   - Standardization of data using `StandardScaler`.
   - Handling infinite and missing values.

5. **Feature Engineering**:
   - Calculation of Variance Inflation Factor (VIF) for assessing multicollinearity.
   - Backward elimination process for variable selection.

6. **Model Building**:
   - Splitting data into training and testing sets.
   - Fitting a linear regression model using Ordinary Least Squares (OLS).
   - Leave-One-Out Cross-Validation for model evaluation.
   - Calculation of Mean Absolute Error (MAE).

7. **Model Diagnostics**:
   - Various tests for regression assumptions (e.g., linearity, homoscedasticity).
   - Application of Newey-West estimator for robust standard errors.

8. **Residual Analysis**:
   - Plotting residuals against fitted values.
   - Q-Q plot for residual normality assessment.

## Usage

To use this script, ensure that the required libraries are installed and the dataset is accessible. Adjust the file path to the dataset as necessary. The script can be run in a Python environment or Google Colab.

## Note

This script is tailored for a specific dataset and may require modifications for use with other datasets. It provides a comprehensive approach to regression analysis, suitable for educational purposes and as a template for similar data analysis tasks.
