# Financial Performance Analysis

[![Language](https://img.shields.io/badge/Language-Python-blue.svg)](https://python.org/)
[![Tool](https://img.shields.io/badge/Tool-Excel-green.svg)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Tool](https://img.shields.io/badge/Tool-Tableau-orange.svg)](https://www.tableau.com/)
[![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow.svg)](https://colab.research.google.com/)

## 📋 Project Overview

This project conducts a comprehensive analysis of companies' financial data to identify patterns and trends that affect **EBITDA** (Earnings Before Interest, Taxes, Depreciation, and Amortization). The analysis aims to provide actionable insights for data-driven business decision-making.

### 🎯 Main Research Question
**Does financial performance affect the EBITDA of a company?**

### 🔍 Sub-questions Addressed
- What is the relationship between Enterprise Value and EBITDA?
- What is the relationship between Market Capitalization and EBITDA?
- What is the relationship between Revenue Growth and EBITDA?
- What is the relationship between Net Income Growth and EBITDA?
- What is the relationship between Debt Growth and EBITDA?

## 📊 Dataset Description

The dataset contains financial statistics for **1,577 companies** including:
- Financial ratios
- Growth rates
- M-Score values
- EBITDA values
- Gross profit and net profit margins
- Return on assets
- Enterprise value and market capitalization data

**Dependent Variable:** EBITDA  
**Independent Variables:** Enterprise Value, Market Capitalization, Revenue Growth, Net Income Growth, Debt Growth

## 🛠 Methodology & Tools

### Analysis Techniques
1. **Descriptive Analysis**
   - Measures of Central Tendency (Mean, Median, Mode)
   - Measures of Dispersion (Range, Variance, Standard Deviation, IQR)

2. **Regression Analysis**
   - Linear regression models for each independent variable
   - Correlation coefficient analysis
   - R-squared evaluation

3. **Data Visualization**
   - Excel dashboards with interactive charts
   - Tableau dashboards for advanced visualization

4. **Predictive Analytics**
   - Machine Learning models using Python
   - SMOTE (Synthetic Minority Oversampling Technique)
   - Fraud detection using M-Score values

### Tools & Technologies
- **Microsoft Excel** - Data cleaning, descriptive analysis, dashboards
- **Tableau** - Advanced data visualization and interactive dashboards
- **Python** - Machine learning and predictive analysis
- **Google Colab** - Cloud-based Python environment
- **Libraries Used**: Scikit-learn, Pandas, NumPy, Matplotlib

## 📈 Key Findings

### Descriptive Statistics (EBITDA)
- **Mean**: $388,207,231.7
- **Median**: $211,556,000
- **Mode**: $114,044,000
- **Distribution**: Positively skewed (Mean > Median > Mode)
- **Range**: $4,772,791,000
- **Standard Deviation**: $589,270,896

### Regression Analysis Results

| Variables | R² (Excel) | R² (ML) | Correlation (r) | Relationship Strength |
|-----------|------------|---------|-----------------|----------------------|
| EBITDA vs Enterprise Value | 0.410 | 0.390 | 0.640 | **Strong** |
| EBITDA vs Market Cap | 0.270 | -0.003 | 0.520 | Moderate |
| EBITDA vs Revenue Growth | 0.003 | -0.003 | 0.060 | Weak |
| EBITDA vs Net Income Growth | 0.005 | -0.003 | 0.070 | Weak |
| EBITDA vs Debt Growth | 0.002 | -0.002 | 0.050 | Weak |

### Top Performing Companies
**By Revenue Growth:**
- EC: 0.8%
- CLVT-PA: 0.4%
- TSM: 0.3%
- SONY: 0.1%



## 📊 Visualizations

The project includes:
- **Excel Dashboard**: Pie charts showing EBITDA distribution across companies, line graphs comparing accounts payable vs receivables
- **Tableau Dashboard**: Interactive visualizations of revenue growth, gross profit margins, and accounts receivables analysis

## 🔬 Machine Learning Models

### Models Implemented
1. **Linear Regression** - Primary analysis tool
2. **Logistic Regression** - Classification accuracy testing
3. **SMOTE Balancing** - Handling imbalanced datasets
4. **Fraud Detection** - Using M-Score values

### Model Performance
- Enterprise Value vs EBITDA: **39% accuracy** (R² = 0.39)
- Revenue Growth predictions: **83.54% accuracy** (Logistic Regression)
- Fraud Detection: **95.25% prediction score**

## ⚠️ Limitations

- Dataset limitations and potential observer bias
- Removal of outliers using IQR may have reduced dataset size
- Machine learning models show varying accuracy levels
- Some null values and data quality issues affect predictive accuracy



## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
