# Descriptive Analytics & Data Preprocessing on Sales & Discounts Dataset

An end-to-step exploratory data analysis (EDA) and data preprocessing project in Python. This project evaluates central tendency, data dispersion, outlier boundaries, and prepares raw retail sales data for machine learning models using standardization and categorical dummy encoding.

---

## 📌 Project Overview

Raw retail sales datasets frequently contain features across differing scales (e.g., quantities vs. monetary amounts) and categorical attributes that cannot be ingested directly into statistical models. 

This project demonstrates:
- **Descriptive Statistics**: Measuring mean, median, mode, and standard deviation across numerical attributes.
- **Exploratory Data Visualization**: Diagnosing skewness, distribution spread, and anomalies using histograms, KDE plots, and boxplots.
- **Categorical Frequency Analysis**: Analyzing class frequency distributions through bar charts.
- **Feature Scaling**: Transforming continuous attributes using Z-score standardization ($z = \frac{x - \mu}{\sigma}$).
- **Categorical Encoding**: Converting categorical features into binary dummy variables via One-Hot Encoding (`drop_first=True` to prevent multicollinearity).

---

## 📁 Repository Structure

```text
├── sales_data_with_discounts.csv   # Primary dataset containing sales & discount metrics
├── Descriptive_Analytics.ipynb     # Jupyter Notebook containing analysis, plots & code
├── requirements.txt                # List of required Python packages
└── README.md                       # Project documentation and summary

