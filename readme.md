# 📊 Sales Performance Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 📌 Overview
This project analyzes retail sales data to uncover business insights related to revenue trends, regional performance, customer segments, product sales, and shipping efficiency. The analysis demonstrates a complete workflow from data cleaning and preprocessing to exploratory analysis and visualization.

## 🎯 Business Objective
The goal of this project is to transform raw retail transaction data into actionable business insights that can support decision-making.

**Key questions explored:**
- How do sales change over time?
- Which regions and states generate the most revenue?
- Which customer segments contribute the most sales?
- Which products and sub-categories are top performers?
- How does shipping performance vary by ship mode?

## 💡 Key Metrics
- **Total Sales:** ⭐ **$872,363.12**
- **Total Orders:** 🛒 **1,975**
- **Total Customers:** 👥 **736**
- **Average Sales per Order:** 💵 **$441.70**

## 🔍 Key Findings
- **High Volume:** Revenue reached **$872K+** across **1,975 orders** from **736 customers**.
- **Geographic Concentration:** Sales performance varied significantly across regions and states, showing strong geographic ties.
- **Pareto Principle:** A small set of sub-categories and products contributed a disproportionately large share of total revenue.
- **Segment Behavior:** Customer segments showed different spending patterns, indicating clear opportunities for targeted sales strategies.
- **Shipping Logistics:** Shipping performance behaved as expected: **Standard Class** had the longest delivery times, while **Same Day** was the fastest.

## 📌 Recommendations
- **Target Top Performers:** Focus inventory planning and promotional efforts on the highest-performing regions and states.
- **Prioritize Winners:** Double down on top-selling products and sub-categories in future marketing campaigns.
- **Growth Opportunities:** Investigate lower-performing geographic areas to identify structural issues or new growth verticals.
- **Optimize Shipping:** Use faster shipping methods strategically for high-value or priority customer segments.
- **Next Steps:** Extend the analysis with profit, discount, and return metrics to form a more complete picture of business health.

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib (Data Visualization)
- **Environment:** Jupyter Notebook

## 🧹 Data Cleaning & Preparation
To ensure high data integrity, the raw dataset was processed through the following steps:
- **Type Conversion:** Converted `Order Date` and `Ship Date` into datetime formats, and cast `Sales` into workable numeric types.
- **Standardization:** Removed duplicate rows and entries containing missing critical values (`Order Date`, `Sales`).
- **Feature Engineering:** Created derived temporal columns for time-series analysis:
  - `Order Year`, `Order Month`, `Order Month Name`, `Year-Month`
- **Metric Creation:** Calculated `Shipping Delay Days` using the exact difference between `Ship Date` and `Order Date`.

## 📈 Analysis Performed
This analytical report deep-dives into:
- Monthly sales trends & seasonality
- Sales distribution by geographic region and state
- Revenue breakdowns by customer segment
- Top 10 lists for Sub-categories, Products, and States
- Average shipping delay comparisons by logistics mode

## 📊 Visualizations

### 📅 Monthly Sales Trend
*Shows how revenue changes over time and highlights possible seasonality and growth constraints.*
<div align="center">
  <img src="images/monthly_sales_trend.png" alt="Monthly Sales Trend" width="80%">
</div>

### 🌍 Sales by Region
*Compares total sales across regions to determine geographic dominance.*
<div align="center">
  <img src="images/sales_by_region.png" alt="Sales by Region" width="80%">
</div>

### 👥 Sales by Customer Segment
*Reveals which distinct customer segment actively contributes the most overall revenue.*
<div align="center">
  <img src="images/sales_by_segment.png" alt="Sales by Segment" width="80%">
</div>

### 🗺️ Top 10 States by Sales
*Highlights the strongest-performing individual states inside the regions by total volume.*
<div align="center">
  <img src="images/top_10_states.png" alt="Top 10 States by Sales" width="80%">
</div>

### 🏆 Top 10 Sub-Categories by Sales
*Identifies the highest-performing product sub-categories driving massive revenue generation.*
<div align="center">
  <img src="images/top_10_subcategories.png" alt="Top 10 Sub-Categories by Sales" width="80%">
</div>

### 📦 Top 10 Products by Sales
*Hones in on the specific product SKUs generating the absolute most revenue.*
<div align="center">
  <img src="images/top_10_products.png" alt="Top 10 Products by Sales" width="80%">
</div>

### 🚚 Average Shipping Delay by Ship Mode
*Compares real-world delivery speeds across all available shipping logistics methods.*
<div align="center">
  <img src="images/shipping_delay_by_mode.png" alt="Shipping Delay by Ship Mode" width="80%">
</div>

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/sales-performance-analysis.git
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
│   ├── sales_by_segment.png
│   ├── top_10_states.png
│   ├── top_10_subcategories.png
│   ├── top_10_products.png
│   └── shipping_delay_by_mode.png
└── README.md                   # Project documentation (You are here!)
```

---
*Created by [Ahmad Syafi](https://github.com/ahmd-byte) - Data Analyst*