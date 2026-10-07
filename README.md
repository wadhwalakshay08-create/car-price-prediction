# Car Price Prediction

A Machine Learning project that predicts the selling price of used cars using car-related features.

## Project Overview

The goal of this project is to predict car selling prices based on features such as year, kilometers driven, fuel type, seller type, transmission, owner, mileage, engine capacity, and number of seats.

## Machine Learning Workflow

1. Load the dataset
2. Explore the data
3. Handle missing values
4. Encode categorical features
5. Separate features and target
6. Split data into training and testing sets
7. Apply StandardScaler
8. Apply PCA for dimensionality reduction
9. Train Random Forest Regressor
10. Perform hyperparameter tuning using GridSearchCV
11. Evaluate the model using R² Score
12. Predict car price using user input

## Model Used

### Random Forest Regressor

Random Forest Regressor is an ensemble Machine Learning algorithm that combines multiple decision trees to make numerical predictions.

## Model Performance

- Train R² Score: **98%**
- Test R² Score: **93%**

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest Regressor
- StandardScaler
- PCA
- GridSearchCV
- Joblib

## Features

- Data preprocessing
- Missing value handling
- Categorical encoding
- Feature scaling
- PCA dimensionality reduction
- Hyperparameter tuning
- Car price prediction
- User input-based prediction

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
