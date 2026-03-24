## Movies & TV Shows Analysis

## Project Overview

This project analyzes a dataset of movies and TV shows to uncover trends in content production, genres, and countries.

The goal is to understand how content distribution evolves over time and what types of content are most popular.

---

## Dataset

Dataset: Netflix Titles

Main features:

- type — Movie or TV Show  
- date_added — when content was added  
- country — production country  
- listed_in — genres  

---

## Tools Used

- Python
- pandas
- matplotlib

---

## Key Steps

### 1. Data Cleaning

- Converted `date_added` to datetime
- Extracted **year_added**
- Handled missing values

---

### 2. Feature Engineering

- Extracted genres from `listed_in`
- Created genre list for analysis

---

### 3. Analysis

- Content added per year
- Top genres
- Top countries
- Distribution of Movies vs TV Shows

---

## Visualizations

- Line chart: Content added over time
- Bar chart: Top genres
- Bar chart: Top countries
- Pie chart: Movies vs TV Shows

---

## Key Insights

- Content production has increased over time.
- A small number of genres dominate the platform.
- Certain countries produce significantly more content.
- Movies dominate over TV shows.
