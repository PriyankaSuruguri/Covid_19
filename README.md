# COVID-19 Prediction Using Machine Learning Models
## Overview
This project develops machine learning models to predict COVID-19 cases and fatalities across U.S. counties. The dataset includes attributes such as date, county, state, FIPS code, number of cases, and number of deaths. The study employs Linear Regression, Decision Tree Regression, Random Forest Regression, Support Vector Regression (SVR), and XGBoost Regression to develop predictive models.

## Abstract
This project develops machine learning models to predict COVID-19 cases and fatalities across U.S. counties. The dataset includes attributes such as date, county, state, FIPS code, number of cases, and number of deaths. The study employs Linear Regression, Decision Tree Regression, Random Forest Regression, Support Vector Regression (SVR), and XGBoost Regression to develop predictive models.

## Objective
The primary objective of this study is to develop and evaluate machine learning models for predicting COVID-19 cases and fatalities based on available data attributes. By comparing the performance of different algorithms, the study aims to identify the most effective model for forecasting COVID-19 trends, thereby aiding public health responses.

## Methodology
- Data Acquisition: Utilized The New York Times' COVID-19 dataset, encompassing cumulative case and death counts across U.S. counties and states over time.
- Data Preprocessing:
Missing Data Management: Employed imputation techniques to address gaps, ensuring dataset completeness.
Feature Engineering: Developed pertinent features to enhance model predictive capabilities.
Data Normalization: Standardized numerical attributes to facilitate uniform model training.
- Exploratory Data Analysis (EDA):
Univariate and Bivariate Analysis: Assessed individual feature distributions and inter-feature relationships to uncover underlying patterns.
- Model Development:
Algorithm Implementation: Constructed predictive models using Linear Regression, Decision Tree Regression, Random Forest Regression, Support Vector Regression (SVR), and XGBoost Regression to capture both linear and complex non-linear trends.
Model Evaluation:
- Performance Metrics: Assessed models using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to determine predictive accuracy.
## Model Evaluation:
- Metrics Used: Evaluated models using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
- Performance Comparison: Compared the performance of all models to identify the most accurate predictor.
## Results
![Covid_19](Covid_image.png)

## Conclusion
This study demonstrates the effectiveness of machine learning algorithms in predicting COVID-19 cases and fatalities. Ensemble methods, particularly Random Forest and XGBoost, outperform individual models, suggesting their potential for accurate forecasting in public health applications. Future work could involve incorporating additional features, such as vaccination rates and mobility data, to further enhance prediction accuracy.
