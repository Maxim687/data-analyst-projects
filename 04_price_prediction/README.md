## Apartment Price Prediction

## Project Overview

This project builds a machine learning model to predict apartment prices based on key features such as area, number of rooms, floor, and district.

The goal is to understand how different factors influence price and to build a predictive model.

---

## Dataset

The dataset was synthetically generated and includes:

- area — apartment size (m²)  
- rooms — number of rooms  
- floor — floor number  
- district — location category  
- price — target variable  

---

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- scikit-learn

---

## Key Steps

### 1. Data Preparation

- Generated synthetic dataset
- Checked for missing values
- Defined features (X) and target (y)

---

### 2. Model Training

- Train/test split (80/20)
- Linear Regression model

---

### 3. Evaluation

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)

---

### 4. Prediction

- Predicted price for new apartment data

---

## Visualizations

- Scatter plot: Real vs Predicted prices
- Regression line: Area vs Price

---

## Key Insights

- Area has the strongest impact on price.
- District significantly affects pricing.
- The model captures general trends but includes noise (simulated market variability).
