# Exploratory Data Analysis (EDA) Report

# Project 5: Retail Sales Analysis Dashboard

## 1. Objective

The objective of this project is to analyze the Sample Superstore dataset to identify sales trends, profitability patterns, customer segments, regional performance, and business opportunities. The project demonstrates data cleaning, statistical analysis, visualization, and business insight generation using Python.

---

# 2. Dataset Information

- **Dataset:** Sample Superstore Dataset
- **Source:** Kaggle
- **Total Records:** 9,994
- **Features:** 21

The dataset contains information about customer orders, product categories, sales, discounts, profits, shipping details, and geographical regions.

---

# 3. Data Cleaning

The following preprocessing steps were performed:

- Loaded the dataset into Pandas.
- Examined dataset structure and data types.
- Checked for missing values.
- Removed duplicate records.
- Verified data consistency.
- Detected outliers in the **Sales** column using the IQR method.
- Treated outliers by capping extreme values.

---

# 4. Statistical Analysis

The following statistical measures were calculated for numerical columns:

- Mean
- Median
- Mode
- Variance
- Standard Deviation

These statistics summarized the distribution of Sales, Profit, Quantity, Discount, and other numerical variables.

---

# 5. Outlier Detection

Outliers were identified in the **Sales** column using the Interquartile Range (IQR) method.

### Steps Performed

- Calculated Q1 and Q3
- Computed the IQR
- Determined lower and upper limits
- Identified outliers
- Treated extreme values using the capping method

This reduced the influence of unusually large sales values while preserving the dataset.

---

# 6. Correlation Analysis

A correlation matrix was generated to examine relationships among numerical variables.

### Key Observations

- Sales and Profit showed a generally positive relationship.
- Discounts negatively affected Profit.
- Quantity had a moderate relationship with Sales.
- High discounts often resulted in reduced profitability.

The correlation heatmap visually highlighted these relationships.

---

# 7. Data Filtering and Sorting

The dataset was filtered to analyze:

- Orders with Sales greater than 500
- Furniture category orders

The dataset was sorted by Sales to identify the highest-value transactions.

---

# 8. GroupBy Analysis

The following analyses were performed:

- Total Sales by Category
- Total Profit by Region
- Average Discount by Customer Segment

These analyses helped compare business performance across different categories and regions.

---

# 9. Visualizations

The following visualizations were created:

- Bar Graph – Sales by Category
- Line Graph – Sales Trend
- Histogram – Sales Distribution
- Scatter Plot – Sales vs Profit
- Correlation Heatmap

These charts provided insights into sales performance, customer behavior, and profitability.

---

# 10. Business Insights

- Technology generated the highest overall sales revenue.
- Office Supplies recorded the largest number of customer orders.
- Furniture products showed inconsistent profitability.
- High discounts significantly reduced profit margins.
- The West and East regions contributed strongly to total sales and profit.
- Some high-sales transactions still resulted in financial losses due to excessive discounts.

---

# 11. Recommendations

- Reduce excessive discounts on low-profit products.
- Increase inventory for high-performing product categories.
- Improve marketing efforts in underperforming regions.
- Monitor products with high sales but low profitability.
- Optimize pricing strategies to maximize profit.

---

# 12. Conclusion

The Sample Superstore dataset was successfully cleaned and analyzed. Statistical analysis, GroupBy operations, and visualizations provided meaningful business insights into sales performance and profitability. The project demonstrates a complete retail sales analysis workflow using Python and highlights opportunities to improve business performance through data-driven decision-making.

---

# Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

# Author

**Tumma Maneeth Reddy**
