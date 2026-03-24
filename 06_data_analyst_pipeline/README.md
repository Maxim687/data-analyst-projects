## User Behavior & Conversion Prediction Pipeline

## Project Overview

This project simulates a real-world data analyst workflow, combining exploratory data analysis and machine learning.

The goal is to understand user behavior and predict whether a user will make a purchase.

---

## Dataset

The dataset was synthetically generated and includes:

- user_id — unique user identifier  
- country — user location  
- session_time — time spent in app  
- age — user age  
- device — device type  
- purchases — target (0/1)  

---

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Key Steps

### 1. Data Preparation

- Generated synthetic dataset
- Checked for missing values
- Encoded categorical variables:
  - device (binary)
  - country (one-hot encoding)

---

### 2. Exploratory Data Analysis

- Average session time
- Conversion rate
- Conversion by country
- Session time vs purchase (boxplot)

---

### 3. Machine Learning

- Logistic Regression model
- Train/test split

---

### 4. Evaluation

- Accuracy score
- Feature importance via model coefficients

---

## Visualizations

- Boxplot: session time vs purchase
- Bar chart: conversion by country

---

## Key Insights

- Users with longer sessions are more likely to purchase.
- Device type influences conversion.
- Country differences suggest market-specific behavior.
