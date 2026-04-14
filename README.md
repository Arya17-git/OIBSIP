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

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------##TASK-3 Data Cleaning

## Project Overview
This project focuses on the **Data Cleaning** phase of the data analytics lifecycle. Using a global dataset of trending YouTube videos, I implemented a robust cleaning pipeline to ensure data integrity, handle missing values, and prepare the dataset for future analysis or segmentation.

## Dataset
Due to the large file size (approx. 500MB), the raw data is not hosted directly in this repository. 
*   **Source:** datasnaek/youtube-new (https://kaggle.com)
*   **Description:** Daily record of the top trending YouTube videos across multiple regions (US, GB, DE, CA, FR, etc.).

## Data Cleaning Implementation
The project addresses the five pillars of data cleaning:

1. **Data Integrity:** Verified logical consistency (e.g., ensuring likes do not exceed views) and corrected time-sequence errors between publish and trending dates.
2. **Missing Data Handling:** Identified gaps in video descriptions and tags, applying `fillna()` strategies to maintain dataset usability without losing records.
3. **Duplicate Removal:** Developed a strategy to handle "re-trending" videos by keeping only the peak performance record (highest views) for each unique `video_id`.
4. **Standardization:** Unified date formats from `YY.DD.MM` to ISO standards, standardized text casing, and mapped `category_id` values to human-readable names using JSON metadata.
5. **Outlier Detection:** Used the **Interquartile Range (IQR)** method to detect viral mega-hits. Implemented three handling strategies: Trimming, Log Transformation, and Categorical Labeling.

## Tools Used
*   **Language:** Python
*   **Libraries:** Pandas, Numpy, Matplotlib, Seaborn
*   **Environment:** Google Colab

---
**Intern:** Arya Tiwari  
**Organization:** Oasis Infobyte  
**Domain:** Data Analytics
