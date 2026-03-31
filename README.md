# NYC Taxi Fare Prediction

**Project Overview**
This project focuses on predicting taxi fares in New York City using machine learning techniques. The goal is to build an accurate regression model that estimates fare prices based on trip details such as distance, pickup/drop-off locations, and timestamps.This project demonstrates end-to-end data science workflow including data preprocessing, feature engineering, model training, and evaluation.

**Objectives**
- Analyze NYC taxi trip data
- Clean and preprocess large-scale real-world data
- Engineer meaningful features for better prediction
- Build and compare multiple regression models
- Evaluate model performance using appropriate metrics

**Dataset**
The dataset includes:
- Pickup & drop-off coordinates
- Passenger count
- Date & time of trip
- Fare amount (target variable)
  
**Workflow**
**1. Data Preprocessing**
- Handled missing values and outliers
- Filtered unrealistic coordinates and fares
- Converted datetime fields
**2. Feature Engineering**
- Extracted features like:
  - Hour of day
  - Day of week
  - Calculated trip distance using coordinates
**3. Model Building**
- Linear Regression
- Random Forest Regressor
**4. Model Evaluation**
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

**Results**
- Achieved strong prediction performance with ensemble models
- Random Forest performed better compared to baseline linear models
- Feature engineering significantly improved accuracy

**Key Learnings**
- Importance of data cleaning in real-world datasets
- Feature engineering can drastically impact model performance
- Ensemble models handle non-linearity better than simple regression
