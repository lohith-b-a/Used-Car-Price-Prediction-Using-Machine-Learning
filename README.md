# Machine Learning Project: Used Car Price Prediction for Business Strategy

## Overview

This project applies machine learning to predict the resale prices of used cars. The goal is to support a used car dealership in setting fair, competitive prices by modeling key features such as brand, year, mileage, fuel type, and accident history. Several regression models were evaluated to determine the most accurate price prediction strategy.

## Business Problem

The dealership is losing revenue due to inconsistent pricing strategies. Some cars are overpriced and sit in inventory too long, while others are underpriced and reduce profit margins. This project solves that problem by building a predictive model that estimates a fair price for each vehicle, helping the business:

- Maximize profit margins
- Price vehicles competitively
- Reduce delays in inventory movement
- Improve customer trust with fair pricing

## Dataset Summary

- Source: Kaggle – Used Car Price Prediction Dataset
- Size: ~8,000 records
- Features: Brand, Model, Year, Mileage, Fuel Type, Transmission, Accident History, Color, Selling Price

## Workflow

1. Data Cleaning & Preprocessing
   - Renamed and standardized column names
   - Removed duplicates and handled missing values
   - Feature engineering and encoding

2. Model Building
   - Trained Gradient Boosting, Random Forest, Decision Tree, Polynomial Regression
   - Compared models using R² Score and RMSE
   - Selected the best model based on accuracy and generalizability

3. Model Evaluation
   - Analyzed model performance on training and validation data
   - Validated the final model using unseen test data

4. Visualizations
   - Distribution of predicted vs actual prices
   - Scatter plots and residual analysis
   - Model comparison visuals

## Model Performance

| Model                  | R² Score | RMSE     |
|------------------------|----------|----------|
| Gradient Boosting      | 0.9999   | 252.06   |
| Random Forest          | 0.9844   | 3450.02  |
| Decision Tree          | 0.9527   | 6009.12  |
| Polynomial Regression  | 0.9554   | 5829.36  |

The Gradient Boosting model outperformed all others and was selected as the final model for deployment.

## Key Insights

- Accident history has a significant impact on resale value
- Mileage and vehicle age are strong predictors of price
- Diesel vehicles tend to retain value better than petrol cars
- Final model offers high accuracy and generalization across test data

## Tools and Technologies

- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn, plotly
- scikit-learn (regression models, evaluation metrics)

## Skills Demonstrated

- Supervised machine learning
- Regression modeling and evaluation
- Data preprocessing and feature engineering
- Business-oriented problem solving
- Communicating findings through visual storytelling

## Author

Lohith Basavanahalli Anjinappa  

