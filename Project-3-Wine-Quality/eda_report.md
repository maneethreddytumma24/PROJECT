# Exploratory Data Analysis (EDA) Report

# Project 3: Wine Quality Exploratory Data Analysis

## 1. Objective

The objective of this project is to analyze the Wine Quality dataset to identify the factors influencing wine quality. The project focuses on data cleaning, statistical analysis, outlier detection, correlation analysis, and visualization using Python.

---

# 2. Dataset Information

- **Dataset:** Wine Quality (Red Wine)
- **Source:** UCI Machine Learning Repository
- **Records Before Cleaning:** 1,599
- **Records After Removing Duplicates:** 1,359
- **Features:** 12

---

# 3. Data Cleaning

The following preprocessing steps were performed:

- Loaded the dataset into Pandas.
- Checked the dataset structure and data types.
- Verified missing values.
- Removed duplicate records.
- Confirmed that the cleaned dataset contained no missing values.
- Treated outliers in the **Alcohol** column using the IQR (Interquartile Range) method.

---

# 4. Statistical Analysis

The following statistical measures were calculated for all numerical columns:

- Mean
- Median
- Mode
- Variance
- Standard Deviation

These statistics helped summarize the distribution and spread of the wine attributes.

---

# 5. Outlier Detection

Outliers were detected in the **Alcohol** column using the IQR method.

### Steps Performed

- Calculated the first quartile (Q1)
- Calculated the third quartile (Q3)
- Computed the Interquartile Range (IQR)
- Determined lower and upper limits
- Identified outliers
- Treated extreme values by capping them within the acceptable range

This approach reduced the impact of extreme observations while preserving the dataset.

---

# 6. Correlation Analysis

A correlation matrix was generated to measure the relationship between numerical variables.

### Observations

- Alcohol showed a positive relationship with wine quality.
- Volatile acidity showed a negative relationship with quality.
- Sulphates had a moderate positive correlation with quality.
- Density was negatively correlated with alcohol.

The correlation heatmap provided a visual representation of these relationships.

---

# 7. Data Filtering and Sorting

The dataset was filtered to analyze:

- Wines with quality greater than or equal to 7
- Wines with alcohol content greater than 12%

The dataset was also sorted by quality to identify the highest-rated wines.

---

# 8. GroupBy Analysis

The following analyses were performed:

- Average alcohol content by wine quality
- Average pH by wine quality
- Average sulphates by wine quality

These analyses helped compare the characteristics of wines across different quality levels.

---

# 9. Visualizations

The following visualizations were created:

- Bar Graph – Wine Quality Distribution
- Histogram – Alcohol Distribution
- Line Graph – Alcohol Content
- Scatter Plot – Alcohol vs Quality
- Box Plot – Alcohol Distribution
- Correlation Heatmap

These charts helped identify patterns, trends, distributions, and relationships among the variables.

---

# 10. Key Findings

- Most wines have quality ratings between **5 and 6**.
- Higher-quality wines generally contain higher alcohol content.
- Volatile acidity tends to decrease as wine quality improves.
- Sulphates show a positive association with wine quality.
- Duplicate records were successfully removed.
- Outliers were detected and treated without removing observations.

---

# 11. Conclusion

The Wine Quality dataset was successfully cleaned and analyzed. Statistical analysis, outlier detection, correlation analysis, and visualizations provided valuable insights into the factors affecting wine quality. The project demonstrates a complete exploratory data analysis workflow using Python and highlights the importance of alcohol content and other chemical properties in determining wine quality.

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
