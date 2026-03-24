## Titanic Survival Prediction

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning classification models.

The goal is to identify key factors influencing survival.

---

## Dataset

Dataset: Titanic Dataset

Main features:

- Pclass — passenger class  
- Sex — gender  
- Age — age  
- SibSp — number of siblings/spouses  
- Parch — number of parents/children  
- Fare — ticket fare  
- Embarked — port of embarkation  

Target:

- Survived (0/1)

---

## Tools Used

- Python
- pandas
- matplotlib
- scikit-learn

---

## Key Steps

### 1. Data Cleaning

- Removed irrelevant columns (Name, Ticket, Cabin, PassengerId)
- Filled missing values:
  - Age → mean
  - Embarked → mode
- Encoded categorical variables

---

### 2. Model Training

- Logistic Regression
- Random Forest Classifier

---

### 3. Evaluation

- Accuracy score
- Confusion matrix
- Classification report (precision, recall, f1-score)

---

### 4. Feature Importance

- Analyzed coefficients from Logistic Regression
- Compared feature impact

---

## Visualizations

- Confusion matrix

---

## Key Insights

- Gender is the most influential feature (female survival higher).
- Passenger class significantly impacts survival.
- Random Forest improves performance over Logistic Regression.
