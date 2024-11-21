
Overview
This project predicts used car sale prices based on car characteristics as part of a Kaggle forecasting competition. The predictions will assist car dealers in pricing strategies and help buyers evaluate the fairness of listed prices.

Project Workflow
1. Forecasting Problem

The goal is to predict used car sale prices based on various car characteristics.

Accurate forecasts can:

Aid car dealers in setting competitive and profitable prices.

Provide customers with tools to identify fair deals.

Enhance market transparency in the used car industry.

2. Evaluation Criteria
Models are evaluated using Mean Squared Error (MSE). The lowest MSE determines the best model.

3. Dataset Overview

Training Data: 38 features + target variable (price).

Test Data: 37 features.

Data Types: Numerical and categorical.

Unique ID: vin (excluded from modeling).

4. Tasks
Data Cleaning:

Extract numerical values from mixed-type columns (e.g., back_legroom).
Impute missing values.

Encode categorical features (map infrequent values to other and encode appropriately).

Transform dates into numeric features (e.g., numeric_days).

Exploratory Data Analysis (EDA): Analyze relationships between features and price (heatmap) & Visualize data trends patterns.

Machine Learning Model: Tuning hyper parameters, train and test XGBoost, Random Forest, and KNN regressors for price prediction.

Submit forecasts to Kaggle.
