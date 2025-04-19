# DSAI Mini Project

## Dataset
Our mini project focuses on the Melbourne housing situation, and is inspired by [this dataset from Kaggle](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot/data)


[![Watch the Project Video](path/to/video_thumbnail.jpg)](path/to/video.mp4 "Project Video")

## Table of Contents 

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Problem Definition](#problem-definition)
- [Data Preparation & Cleaning](#data-preparation--cleaning)
- [Exploratory Data Analysis (EDA) & Visualization](#exploratory-data-analysis-eda--visualization)
- [Machine Learning Approaches](#machine-learning-approaches)
  - [Random Forest Feature Importance](#random-forest-feature-importance)
  - [Suburb Price Trend & Clustering Analysis](#suburb-price-trend--clustering-analysis)
- [Data-Driven Insights & Recommendations](#data-driven-insights--recommendations)
- [Running the Project](#running-the-project)
- [Future Work](#future-work)
- [Final Remarks](#final-remarks)
- [References](#references)
---

## Overview

This project aims to deliver actionable insights into the real estate market by analyzing housing data. We investigate the following key questions:

1. **Feature Impact:**  
   Which features have the highest impact on price based on feature importance from a Random Forest model?
   
2. **Regional Price Trends:**  
   How has the price trend varied across different regions over time, and can we identify emerging high-value areas?

3. **Suburb Market Competitiveness:**  
   Which suburbs have the most competitive real estate markets based on property count, sales, and price trends?

In addition, the project includes our own problem definition, extensive data preparation and cleaning, exploratory data analysis, multiple machine learning analyses, and final recommendations based on data-driven insights.

---

## Project Structure


---

## Problem Definition

**Our Objective:**  
*Develop actionable insights on the real estate market by identifying key drivers of housing prices, uncovering emerging high‑value areas, and pinpointing the most competitive suburbs. This analysis will guide both strategic investment decisions and market forecasting.*

**Unanswered Questions (Placeholders):**

- **Q1:** Which features have the highest impact on price based on feature importance from a Random Forest model?  
  **[Your Findings: Placeholder]**

- **Q2:** How has the price trend varied across different regions over time, and can we identify emerging high-value areas?  
  **[Your Findings: Placeholder]**

- **Q3:** Which suburbs have the most competitive real estate markets based on property count, sales, and price trends?  
  **[Your Findings: Placeholder]**

---

## Data Preparation & Cleaning

- **Data Loading:**  
  Data is loaded using `pandas` and inspected for missing values and inconsistencies.

- **Date Formatting:**  
  The "Date" column is converted to datetime format and sorted for accurate time series analysis.

- **Handling Categorical Variables:**  
  Variables such as `Type`, `Method`, `CouncilArea`, `Regionname`, and `Suburb` are preprocessed. Interactive visualizations (via Plotly) are used for categories with many levels (e.g., CouncilArea, Suburb).

- **Placeholder for Further Cleaning Tasks:**  
  **[Document any additional cleaning steps or transformations performed]**

---

## Exploratory Data Analysis (EDA) & Visualization

We conducted extensive EDA to gain insights into pricing trends and market competitiveness:

- **Categorical Variable Analysis:**  
  Static visualizations (using Matplotlib/Seaborn) for `Type`, `Method`, and `Regionname` and interactive plots (using Plotly) for `CouncilArea` and `Suburb`.

- **Trend Analysis:**  
  Aggregation of average prices over time by Region and Suburb, computation of percentage changes, and clustering using K-Means.

- **Unanswered/Extra Exploration:**  
  - What additional external factors might correlate with the observed trends? **[Placeholder]**
  - Are there seasonal effects in the pricing data? **[Placeholder]**

---

## Machine Learning Approaches

### Random Forest Feature Importance

- **Objective:**  
  Identify which features are most influential on the housing prices.
  
- **Method:**  
  A Random Forest model was applied (see `Lex_housing_with_updated_data.ipynb`), and feature importances were extracted and ranked.
  
- **Key Findings:**  
  **[Your Feature Importance Findings: Placeholder]**

### Suburb Price Trend & Clustering Analysis

- **Objective:**  
  Analyze how price trends vary across suburbs over time, calculate overall market activity, and pinpoint competitive markets.
  
- **Method:**  
  - Aggregated suburb-level data to compute average price trends and property counts.
  - Applied K-Means clustering after scaling features.
  - Visualized clusters via PCA and scatter plots to display emerging high-value suburbs.
  
- **Key Findings:**  
  **[Your Clustering and Trend Analysis Findings: Placeholder]**

---

## Data-Driven Insights & Recommendations

Based on the analyses, our key insights and recommendations are:

- **Insights:**  
  - **Feature Impact:** _[Insert key insights on feature contributions to price]_.  
  - **Emerging Regions/Suburbs:** _[Insert findings on emerging high-value areas]_.  
  - **Market Competitiveness:** _[Insert insights on suburbs with competitive real estate markets]_.

- **Recommendations:**  
  _[Provide recommendations for investors, policy makers, or other stakeholders based on the findings]_.

---

## Running the Project

1. **Environment Setup:**  
   Ensure Python 3.x is installed with the following libraries:
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

1. **Link**  

## Authors

- Tan Yu Xiu [U2322532B]
- Lex Tan Pengqin [U2322095L]
- Lim Jun, Shawn [U2320477A]