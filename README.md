# Linear Regression Machine Learning Project for House Price Prediction

## Project Overview

This project implements a simple linear regression model to predict house prices in the USA based on various features such as average area income, house age, number of rooms, and population. The model is trained and evaluated to assess its prediction accuracy.

---

## Features Used for Prediction

- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population

---

## Libraries Used

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

---

## Dataset

The dataset **USA_Housing.csv** contains housing data with the following key columns:

- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population
- Price (target variable)

---

## Steps in the Project

1. **Data Import and Exploration**
   - Load dataset using pandas.
   - Explore and visualize data distribution and correlations using seaborn and matplotlib.
   
2. **Exploratory Data Analysis (EDA)**
   - Pairplots, distribution plots, and heatmaps to understand relationships between features and the target variable.

3. **Model Training**
   - Define features (X) and target (y).
   - Split the data into training and test parts (60%-40% split).
   - Train a Linear Regression model using scikit-learn.

4. **Model Evaluation**
   - View model intercept and coefficients.
   - Predict house prices on the test set.
   - Visualize predictions vs actual prices using scatter and distribution plots.
   - Calculate evaluation metrics:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)

---

## How to Run

1. Install required Python libraries (if not installed):

