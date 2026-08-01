# Exploratory Data Analysis (EDA) Report

# Project 4: Diamond Price Analysis

## 1. Objective

The objective of this project is to analyze the Diamonds dataset and understand how different physical characteristics influence diamond prices.

---

# 2. Dataset Information

- Dataset: Diamonds Dataset
- Source: Kaggle
- Records: 53,940
- Features: 10

---

# 3. Data Cleaning

The following preprocessing steps were performed:

- Loaded the dataset into Pandas.
- Checked dataset structure and data types.
- Verified missing values.
- Removed duplicate records.
- Detected price outliers using the IQR method.
- Treated extreme price values by capping them.

---

# 4. Statistical Analysis

The following statistical measures were calculated:

- Mean
- Median
- Mode
- Variance
- Standard Deviation

These statistics helped summarize the numerical features and understand the dataset distribution.

---

# 5. Outlier Detection

Outliers were detected in the **Price** column using the Interquartile Range (IQR) method.

Steps performed:

- Calculated Q1 and Q3
- Computed the IQR
- Determined lower and upper limits
- Identified outliers
- Capped extreme values

---

# 6. Correlation Analysis

A correlation matrix was generated to understand relationships between numerical variables.

### Important Observations

- Carat has the strongest positive correlation with price.
- Diamond dimensions (x, y, z) also positively correlate with price.
- Depth has a weak relationship with price.

---

# 7. Data Filtering and Sorting

The dataset was filtered to analyze:

- Diamonds priced above 10,000
- Ideal cut diamonds

The dataset was sorted by price to identify the most expensive diamonds.

---

# 8. GroupBy Analysis

The following analyses were performed:

- Average price by cut
- Average carat by color
- Average price by clarity

These analyses revealed differences among diamond categories.

---

# 9. Visualizations

The following charts were created:

- Bar Graph
- Histogram
- Line Graph
- Scatter Plot
- Box Plot
- Correlation Heatmap

---

# 10. Business Insights

- Carat is the most influential factor affecting price.
- Ideal cut diamonds dominate the dataset.
- Higher clarity diamonds generally command premium prices.
- Diamond dimensions are strongly associated with pricing.

---

# 11. Conclusion

The Diamonds dataset was successfully cleaned and analyzed. Statistical analysis and visualizations demonstrate that carat weight, clarity, and cut quality are the major factors influencing diamond prices. The project showcases a complete EDA workflow suitable for business analytics.

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
