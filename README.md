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

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Task 3: Data Cleaning & Integrity Analysis 🧹

### 🎯 Project Objective

The goal of this project was to perform an extensive **Data Cleaning** process on the YouTube Trending Video dataset using Python. By unifying multiple regional datasets and addressing inconsistencies, outliers, and missing values, we ensured the data is structurally sound and reliable for high-level business intelligence and content strategy analysis.

### 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab

### 📉 Key Workflow

1. **Data Unification:** Merged multiple regional CSV files into a single master dataset and added `region` tags for better data provenance.
2. **Missing Data Handling:** Utilized `fillna()` to address gaps in `description` and `tags`, ensuring 100% usability for future text analysis.
3. **Standardization:** Unified date formats from `YY.DD.MM` to standard `datetime` 
4. **Integrity & Uniqueness:** Conducted logic checks (Likes vs. Views) and removed `video_id` duplicates to isolate unique performance records.
5. **Outlier Detection:** Applied the **Interquartile Range (IQR)** method and `Log Transformation` to stabilize skewed engagement metrics.

---
**Data Source:** [Kaggle - Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new/data)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Intern:** Arya Tiwari  
**Organization:** Oasis Infobyte  
**Domain:** Data Analytics
