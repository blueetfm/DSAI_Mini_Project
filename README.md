# DSAI Mini Project

## Dataset
Our mini project focuses on the Melbourne housing situation, and is inspired by [this dataset from Kaggle](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot/data)


## Table of Contents 

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Problem Definition](#problem-definition)
- [Methodology](#methodology)
  - [Techniques Used](#techniques-used)
  - [Preprocessing](#preprocessing)
  - [Optimization](#optimization)
- [Insights and Recommendations](#insights-and-recommendations)
- [Future Work](#future-work)
- [Running the Project](#running-the-project)
- [References](#references)
- [Authors](#authors)
---

## Overview

This project aims to deliver actionable insights into the real estate market by analyzing housing data. We investigate the following key questions:

1. **Feature Impact:**  
   Which features have the highest impact on price based on feature importance from a Random Forest model?
   
2. **Regional Price Trends:**  
   How has the price trend varied across different regions over time, and can we identify emerging high-value areas?

3. **Influence of Variables on Prediction Accuracy**  
   How does property age and size influence prediction accuracy in our models?

In addition, the project includes our own problem definition, extensive data preparation and cleaning, exploratory data analysis, multiple machine learning analyses, and final recommendations based on data-driven insights.


---
## Project Structure
1. Exploratory Data Analysis
2. Preparation of Variables
3. Core Analysis and Respective Improvements
4. Conclusion

---

## Problem Definition

**Our Objective:**  
*Develop actionable insights on the real estate market by identifying key drivers of housing prices, uncovering emerging high‑value areas, and pinpointing the most competitive suburbs. This analysis will guide both strategic investment decisions and market forecasting.*

---

## Methodology

### Techniques Used
- Linear Regression
- Polynomial Regression
- Random Forest Regression
- K-Means Clustering

### Preprocessing
- Handling missing values using Decision Tree importance
- Date and Period column transformations
- Ordinal Encoding for categorical features
- Outlier removal and feature selection

### Optimization
- Hyperparameter tuning (GridSearchCV)
- Error analysis (MAE, R²)
- Model validation through train-test split

## Insights and Recommendations
**Insights:**
- Location and size remain the strongest indicators of housing price.
- Eastern and Southern suburbs show strong growth potential.
- Age and extreme property sizes reduce prediction accuracy.
- Ensemble models like Random Forest significantly outperform linear models.

**Recommendations:**
- **Investors**: Focus on Western Metropolitan's growth corridors
- **Developers**: Optimize 3-4 bedroom configurations in family zones
- **Councils**: Monitor overvaluation in 50+ year old properties

## Future Work
- Improve clustering with richer time-based data
- Incorporate economic factors or zoning data
- Build interactive dashboards to visualize trends

---

## Running the Project

1. **Environment Setup:**  
   Ensure Python 3.10 is installed with the following libraries:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - plotly
   - scikit-learn

   Install the dependencies via:

   ```bash
   pip install -r requirements.txt

---

## References

1. https://www.kaggle.com/code/residentmario/simple-techniques-for-missing-data-imputation#Data-missing-at-random-and-not-at-random
2. https://medium.com/@aaryanohekar277/what-is-the-difference-between-a-decision-tree-classifier-and-a-decision-tree-regressor-36641bd6559c

## Authors

- Tan Yu Xiu [U2322532B]
- Lex Tan Pengqin [U2322095L]
- Lim Jun, Shawn [U2320477A]