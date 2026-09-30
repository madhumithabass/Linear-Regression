# Car Mileage Prediction using Regression

## Project Overview

This project focuses on predicting the **mileage of cars** using machine learning regression techniques.

The dataset contains different characteristics of cars such as engine specifications, weight, acceleration, and model year. These features are used to predict the car's fuel efficiency or mileage.

## Problem Statement

Develop a regression model that can predict a car's mileage based on its technical and performance-related features.

## Objective

- Understand the factors that influence car mileage.
- Perform data cleaning and preprocessing.
- Explore relationships between car features and mileage.
- Build regression models for mileage prediction.
- Evaluate and compare model performance.
- Identify the important features affecting mileage.

## Dataset

The dataset contains information about different cars and their specifications.

### Features

| Feature | Description |
|---|---|
| `mpg` | Miles per gallon (target variable) |
| `cylinders` | Number of cylinders in the engine |
| `displacement` | Engine displacement |
| `horsepower` | Engine horsepower |
| `weight` | Weight of the car |
| `acceleration` | Acceleration performance |
| `model_year` | Year in which the car model was manufactured |
| `origin` | Origin of the car |
| `car_name` | Name of the car |

## Target Variable

**`mpg` (Miles Per Gallon)**

The objective is to predict the mileage of a car based on its other features.

## Machine Learning Approach

The project follows these steps:

1. Import the dataset
2. Understand the dataset structure
3. Perform exploratory data analysis
4. Check and handle missing values
5. Detect and handle outliers where required
6. Perform feature preprocessing
7. Split the data into training and testing sets
8. Build regression models
9. Make predictions
10. Evaluate model performance
11. Compare model results
12. Identify important features

## Regression Models

The following regression algorithms can be explored:

- Linear Regression
- Multiple Linear Regression
- Decision Tree Regression
- Random Forest Regression

## Evaluation Metrics

The models can be evaluated using:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

### R² Score

The R² score indicates how well the model explains the variation in car mileage.

A higher R² value indicates that the model explains more of the variation in the target variable.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
Car-Mileage-Prediction/
│
├── dataset/
│   └── car_mileage.csv
│
├── Car_Mileage_Prediction.ipynb
│
├── README.md
│
└── requirements.txt
