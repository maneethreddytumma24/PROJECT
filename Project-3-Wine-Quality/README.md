# 🍷 Project 3: Wine Quality Exploratory Data Analysis

## 📌 Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Wine Quality dataset to understand the factors that influence wine quality. The project includes data cleaning, statistical analysis, outlier detection, correlation analysis, and data visualization using Python.

---

## 📂 Dataset

- **Dataset:** Wine Quality (Red Wine)
- **Source:** UCI Machine Learning Repository
- **Records:** 1,599 (before removing duplicates)
- **Features:** 12

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## 📋 Tasks Performed

- Imported and explored the dataset
- Checked dataset structure and summary statistics
- Identified and removed duplicate records
- Checked for missing values
- Calculated:
  - Mean
  - Median
  - Mode
  - Variance
  - Standard Deviation
- Detected and treated outliers using the IQR method
- Performed correlation analysis
- Filtered and sorted data
- Grouped data using `groupby()`
- Created multiple visualizations

---

## 📊 Visualizations

- 📊 Bar Chart – Wine Quality Distribution
- 📈 Line Graph – Alcohol Content
- 📉 Histogram – Alcohol Distribution
- 🔵 Scatter Plot – Alcohol vs Quality
- 📦 Box Plot – Alcohol Distribution
- 🌡️ Correlation Heatmap

---

## 🔍 Key Findings

- Most wine samples have a quality rating between **5 and 6**.
- Alcohol content generally increases with higher wine quality.
- Several chemical properties show positive or negative correlations with wine quality.
- Duplicate records were removed to improve data quality.
- Outliers in the alcohol column were detected and treated using the IQR method.

---

## 📁 Project Structure

```text
Project-3-Wine-Quality/
│
├── README.md
├── EDA_Report.md
├── Project_3_Wine_Quality_Exploratory_Data_Analysis.ipynb
├── winequality-red.csv
│
└── images/
    ├── bar_graph.png
    ├── histogram.png
    ├── line_graph.png
    ├── scatter_plot.png
    ├── box_plot.png
    └── correlation_heatmap.png
```

---

## 🎯 Conclusion

This project demonstrates a complete exploratory data analysis workflow, including data preprocessing, statistical analysis, correlation analysis, and visualization. The results provide insights into the relationship between chemical properties and wine quality while showcasing practical data analysis skills using Python.

---

## 👨‍💻 Author

**Tumma Maneeth Reddy**
