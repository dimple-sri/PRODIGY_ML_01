# PRODIGY_ML_01 - House Price Prediction using Linear Regression

## Task Description

Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

## Dataset

The project uses the Kaggle House Prices - Advanced Regression Techniques dataset.

The dataset contains information about residential houses and their sale prices.

## Features Used

The following features were selected for the prediction model:

- `GrLivArea` - Above ground living area in square feet
- `BedroomAbvGr` - Number of bedrooms above ground
- `FullBath` - Number of full bathrooms

### Target Variable

- `SalePrice` - The sale price of the house

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab
- Jupyter Notebook

## Machine Learning Algorithm

### Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict a continuous numerical value.

In this project, the model learns the relationship between:

- Living area
- Number of bedrooms
- Number of bathrooms

and predicts the:

- House sale price

## Project Workflow

1. Load the dataset
2. Explore the dataset
3. Select relevant features
4. Select the target variable
5. Split the data into training and testing sets
6. Create a Linear Regression model
7. Train the model
8. Predict house prices
9. Evaluate model performance
10. Visualize actual vs predicted prices

## Model Evaluation

The model is evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results

The model predictions are evaluated by comparing the actual house prices with the predicted house prices.

An Actual vs Predicted House Prices visualization is also included in the Jupyter Notebook.

## Project Files

- `House_Price_Prediction_Linear_Regression.ipynb` - Contains the complete implementation of the Linear Regression model.

## Conclusion

This project demonstrates how Linear Regression can be used to predict house prices based on selected housing features such as square footage, number of bedrooms, and number of bathrooms.
