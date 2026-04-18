# 📊 Sales Performance Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 📌 Overview
This project analyzes a dataset of retail sales to uncover actionable business insights regarding seasonal trends, regional performance, and top-performing product sub-categories. By transforming raw, unorganized sales data into a clear analytical view, the project demonstrates an end-to-end data analysis workflow.

## 🎯 Business Objective
The primary goal is to turn raw sales data into strategic business intelligence. This involves:
- Identifying which product categories drive the most revenue.
- Understanding geographic distribution of sales to optimize regional strategies.
- Spotting monthly sales trends to assist with inventory and forecasting.

## 💡 Key Insights & Metrics
- **Total Revenue:** ⭐ $872,363.12
- **Total Orders Processed:** 🛒 1,975
- **Unique Customers Served:** 👥 736
- **Top Performer:** Identified the top 10 product sub-categories, providing a clear focus for marketing efforts.
- **Regional Dominance:** Highlighted which regions generate the highest sales volume.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib (Data Visualization)
- **Environment:** Jupyter Notebook

## 🧹 Methodology & Data Cleaning
To ensure data integrity before analysis, the following data cleaning and preprocessing steps were applied:
- **Type Casting:** Converted `Order Date` into datetime objects and formatted `Sales` into workable numeric types.
- **Handling Inconsistencies:** Removed duplicate entries and rows containing missing critical values (`Order Date`, `Sales`).
- **Feature Engineering:** Derived new temporal columns (`Order Year`, `Order Month`, `Year-Month`) to enable deep-dive time-series analysis.

## 📈 Visualizations

### 📅 Monthly Sales Trend
*Visualizes the fluctuation of revenue over time, highlighting seasonal peaks and targeted periods for promotional campaigns.*
<div align="center">
  <img src="images/monthly_sales_trend.png" alt="Monthly Sales Trend" width="80%">
</div>

### 🌍 Sales by Region
*Breaks down corporate revenue by geographic location, useful for resource allocation.*
<div align="center">
  <img src="images/sales_by_region.png" alt="Sales by Region" width="80%">
</div>

### 🏆 Top 10 Sub-Categories by Sales
*Identifies the most lucrative product lines driving the bottom line.*
<div align="center">
  <img src="images/top_10_subcategories.png" alt="Top 10 Sub-Categories" width="80%">
</div>

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sales-performance-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sales-performance-analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install pandas matplotlib jupyter
   ```
4. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/sales_analysis.ipynb
   ```

## 📁 Project Structure
```text
sales-performance-analysis/
├── data/
│   ├── sales.csv               # Raw dataset
│   └── sales_cleaned.csv       # Cleaned dataset ready for analysis
├── notebooks/
│   └── sales_analysis.ipynb    # Main analysis notebook
├── images/                     # Exported visualization charts
│   ├── monthly_sales_trend.png
│   ├── sales_by_region.png
│   └── top_10_subcategories.png
└── README.md                   # Project documentation (You are here!)
```

---
*Created by [Ahmad Syafi](https://github.com/yourusername) - Data Analyst*