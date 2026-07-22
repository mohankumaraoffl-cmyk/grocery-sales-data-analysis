# grocery-sales-data-analysis
EDA and Sales Performance Analytics using Python &amp; Pandas
# 🛒 Grocery Chain Sales & Time Categorization Analysis

## 📌 Project Overview
This project focuses on cleaning, categorizing, and analyzing sales transactions for a grocery retail chain using Python and Pandas.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Colab

## 🔑 Key Features & Cleaning
- **Data Quality:** Removed missing values and filtered out invalid negative transactions (`final_amount >= 0`).
- **Date Formatting:** Converted raw text dates to `datetime64` format.
- **Feature Extraction:** Extracted `Month_Name`, `Year`, and `Day_of_Week` for time-series categorization.

## 📊 Business Insights Derived
1. **Top Revenue Month:** March recorded the highest sales volume.
2. **Category Leader:** Beverages and Personal Care aisles generated maximum item volume.
3. **Store Performance:** Summarized total revenue and order velocity across branches.
