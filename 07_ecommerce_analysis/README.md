## E-commerce Sales Analysis

## Project Overview

This project analyzes real-world e-commerce transaction data to uncover revenue patterns, customer behavior, and product performance.

The goal is to identify key drivers of revenue and apply business analytics techniques such as Pareto analysis.

---

## Dataset

Dataset: Online Retail

Main features:

- InvoiceNo — order ID  
- StockCode — product ID  
- Description — product name  
- Quantity — number of items  
- InvoiceDate — transaction date  
- UnitPrice — price per unit  
- CustomerID — customer ID  
- Country — customer location  

---

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- seaborn

---

## Key Steps

### 1. Data Cleaning

- Removed missing CustomerID values
- Filled missing product descriptions
- Removed negative quantities (returns)

---

### 2. Feature Engineering

- Created **Revenue = Quantity × UnitPrice**
- Extracted time features (Year, Month, Day)

---

### 3. Analysis

- Total revenue
- Average order value
- Unique customers
- Revenue by country
- Top products by sales
- Monthly revenue trends

---

### 4. Advanced Analysis

- Pareto Analysis (80/20 rule)
- Top customers by revenue

---

## Visualizations

- Bar chart: Top countries by revenue
- Bar chart: Top products
- Line chart: Monthly revenue
- Pareto curve (cumulative revenue)
- Bar chart: Top customers

---

## Key Insights

- A small percentage of products generate the majority of revenue (Pareto principle).
- Certain countries dominate total sales.
- A few customers contribute a large portion of revenue.
- Sales show variation over time.
