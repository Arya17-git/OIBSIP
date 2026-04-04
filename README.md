# TASK 1: RETAIL SALES ANALYSIS (EDA)

## 📌 Project Overview
This project was completed as part of my **Data Analytics Internship at Oasis Infobyte**. The primary objective was to perform Exploratory Data Analysis (EDA) on a retail sales dataset to uncover consumer trends, purchasing behavior, and seasonal patterns.

## 🛠️ Technologies Used
*   **Environment:** Google Colab
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels

## 📊 Workflow & Techniques Applied
1.  **Data Loading:** Hosted the dataset on GitHub and loaded it into Colab using raw URLs for portability.
2.  **Data Cleaning:** Verified zero null values, handled duplicates, and ensured data types were correct.
3.  **Descriptive Statistics:** Calculated Mean, Median, Mode, and Standard Deviation to understand the central tendency and spread of sales.
4.  **Time Series Analysis:** 
    *   **Stationarity:** Performed the **Augmented Dickey-Fuller (ADF) Test**.
    *   **Smoothing:** Applied **Simple Moving Average (SMA)** and **Exponential Moving Average (EMA)** to reduce noise.
    *   **Seasonality:** Identified peak sales days and monthly trends.
5.  **Customer Demographics:** Segmented spending by **Age Group** and **Gender**.
6.  **Visualization:** Created Line Plots for trends, Bar Charts for categories, and Heatmaps for behavioral correlations.

## 💡 Key Findings
*   **Top Performer:**  Electronics contributed the highest revenue.
*   **Peak Period:** Sales showed a significant spike during the month of June and on Saturdays.
*   **Customer Base:** The primary demographic was 28-40 year olds.

## 🚀 Actionable Recommendations
*   **Inventory:** Increase stock for top-performing categories during identified peak periods.
*   **Marketing:** Target Females of age group 20-30 with personalized offers based on their high spending power.
*   **Stability:** Since the data is stationary, the business should focus on maintaining its current stable customer base while experimenting with mid-week promotions.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Task 2: Customer Segmentation Analysis 📊

## 🎯 Project Objective
The goal of this project was to perform **Customer Segmentation** for an e-commerce platform (iFood) using **K-Means Clustering**. By grouping customers based on their purchase history and demographic data, we can develop targeted marketing strategies to increase retention and revenue.

## 🛠️ Tech Stack
- **Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Scikit-learn (K-Means), Matplotlib, Seaborn
- **Environment:** Google Colab

## 📈 Key Workflow
1.  **Data Cleaning:** Handled missing values in `Income` and removed outliers to ensure clustering accuracy.
2.  **Feature Engineering:** Created a `TotalSpent` metric and renamed `Recency` to `Days_Since_Last_Purchase` for better business clarity.
3.  **Scaling:** Applied `StandardScaler` to normalize features (Income, Spending, and Inactivity).
4.  **Optimal Clusters:** Used the **Elbow Method** to identify **4 distinct customer segments**.


---
**Intern:** Arya Tiwari  
**Organization:** Oasis Infobyte  
**Domain:** Data Analytics
