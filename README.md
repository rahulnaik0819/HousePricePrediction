# House Price Prediction

This project is a machine learning pipeline to predict house prices based on a housing dataset. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, and regression model training and evaluation.

## Dataset

The dataset used is `housing.csv` which contains features such as location coordinates, housing age, number of rooms, etc., and the target variable `median_house_value` representing house prices.

## Technologies Used

- Python 3
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for machine learning models and preprocessing

## Models Implemented

- Support Vector Regression (SVR) with hyperparameter tuning
- Random Forest Regressor
- Linear Regression

## How to Run

1. Clone the repository
2. Place `housing.csv` in the project directory
3. Run the Python script or Jupyter Notebook with the provided code
4. The program will preprocess data, train models, and output mean absolute percentage error (MAPE) for each model

## Results

- Random Forest showed the best accuracy with lowest MAPE
- SVR performance was improved using feature scaling and grid search tuning
- Linear Regression was also evaluated for comparison
