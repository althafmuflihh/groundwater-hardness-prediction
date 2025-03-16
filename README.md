# Groundwater Hardness Prediction with LightGBM

## Project Objective
This project aims to develop a LightGBM regression model to predict groundwater hardness based on chemical composition. The dataset consists of groundwater quality measurements from various states in Mexico, with features including alkalinity, calcium, magnesium, and other chemical properties. The goal is to contribute to solving groundwater issues in Mexico.

## Methods Used
* Machine Learning
* LightGBM Regression
* Data Preprocessing & Feature Engineering

## Evaluation Metrics
* R-squared (R²)
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

## Language
* Python

## Modules Used
* Pandas
* NumPy
* Scikit-Learn
* LightGBM

## Step-by-Step Process

1. **Dataset Analysis & Preprocessing**
    * Handle missing values
    * Check data distribution and outliers
    
2. **Feature Engineering**
    * Select important chemical attributes
    * Normalize numerical features
    
3. **Data Preparation**
    * Split data into training and validation sets (80:20 split)
    * Convert data into LightGBM Dataset format
    
4. **Model Training**
    * Train LightGBM model with hyperparameter tuning
    * Use GridSearchCV for parameter optimization
    
5. **Hyperparameter Tuning**
    * Optimize learning rate, max depth, and number of estimators
    
6. **Model Evaluation**
    * **Metric** | **Training Data** | **Validation Data**
        * R² Score | 0.9211 | 0.7661
    
## Results
Scored **0.91952** on Data Science Academy COMPFEST 2024
