# Banking-project-End-to-End
End-to-end banking analytics project using SQL, Python, and Power BI
# 🏦 Banking Analytics Project

## 📌 Project Overview

This project analyzes banking customer data to understand customer demographics, financial behavior, banking relationships, income levels, loans, deposits, savings, credit card balances, and risk-related characteristics.

The project combines **Python for data analysis and exploratory data analysis (EDA)** with **Power BI for interactive dashboard visualization**.

The goal is to identify meaningful customer patterns and generate business insights that can support better customer segmentation, financial product targeting, and banking decision-making.


## 🎯 Objectives

* Analyze customer demographics and financial characteristics.
* Understand customer income and income-band distribution.
* Analyze deposits, savings, loans, and credit card balances.
* Identify relationships between important financial variables.
* Examine customer loyalty and risk-related characteristics.
* Identify patterns across customer occupations and nationalities.
* Create interactive Power BI dashboards for business reporting.
* Generate actionable banking business insights.


## 🛠️ Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Power BI**
* **Jupyter Notebook**
* **GitHub**



## 📂 Project Structure

```text
Banking-Analytics/
│
├── README.md
├── Python/
│   └── Banking_Analytics.ipynb
│
├── PowerBI/
│   ├── Banking_Dashboard.pbix
│   └── Banking_Dashboard_2.pbix
│
├── Dataset/
│   └── banking-clients.csv
└── requirements.txt
```



## 🔍 Python Analysis

The Python notebook covers the following analysis:

### 1. Data Loading & Exploration

* Imported the banking dataset using Pandas.
* Examined dataset shape and structure.
* Checked data types and basic information.
* Reviewed numerical and categorical variables.

### 2. Data Preparation

* Checked missing values.
* Converted the `Joined Bank` column into datetime format.
* Created an `Income Band` variable using customer estimated income.

Income categories:

* Low
* Mid
* High

### 3. Descriptive Analysis

Used descriptive statistics to understand:

* Age
* Estimated Income
* Superannuation Savings
* Credit Card Balance
* Bank Loans
* Bank Deposits
* Other financial variables

### 4. Customer Segmentation

Analyzed customers based on variables such as:

* Nationality
* Occupation
* Income Band
* Loyalty Classification
* Risk Weighting
* Fee Structure
* Properties Owned

### 5. Correlation Analysis

A correlation matrix was created to identify relationships between financial variables such as:

* Bank Deposits
* Saving Accounts
* Checking Accounts
* Foreign Currency Accounts
* Estimated Income
* Age
* Bank Loans
* Credit Card Balance
* Business Lending
* Properties Owned

### 6. Visualization

The project uses:

* Histograms
* Count plots
* Correlation heatmaps
* Scatter plots
* Regression plots

These visualizations help identify customer behavior and relationships between banking variables.



## 📊 Power BI Dashboard

The Power BI component provides an interactive view of the banking dataset.

The dashboard can be used to explore:

* Customer demographics
* Income distribution
* Banking products
* Deposits and savings
* Loans
* Credit card balances
* Customer segmentation
* Risk-related information
* Customer loyalty

Dashboard screenshots are included in the `Images` folder.

---

## 💡 Key Business Insights

### 💰 Deposits & Savings Behavior

A strong relationship between bank deposits and savings-related accounts indicates similar customer saving and deposit behavior.

This can help banks identify customers with strong saving potential and target them with suitable savings and investment products.

### 📈 Income, Age & Financial Accumulation

Income and age show relationships with several financial balances, suggesting that customer financial behavior may vary across different stages of their financial lifecycle.

Higher-income and older customers may represent potential segments for savings, investment, retirement, and lending products.

### 🏠 Property Ownership

Property ownership shows weaker relationships with several banking variables.

This suggests that property ownership may be influenced by factors beyond the financial variables available in the dataset.

### 🏦 Business & Personal Lending

The relationship between business lending and bank loans indicates that some customers may have both personal and business-related borrowing requirements.

This creates opportunities for banks to better segment customers based on their lending needs.



## 📌 Recommendations

* Develop targeted banking products based on customer income bands.
* Identify high-value customers using deposits, savings and income characteristics.
* Create personalized loan and credit-card offers based on customer financial behavior.
* Segment customers according to loyalty and risk characteristics.
* Use customer financial profiles to improve cross-selling opportunities.
* Monitor customers with significant loan and credit balances.
* Develop different strategies for personal and business banking customers.



## 📈 Business Value

This project demonstrates how banking data can be transformed into actionable insights using:

**Data → Analysis → Visualization → Business Insights**

The analysis can support:

* Customer segmentation
* Product recommendation
* Loan and credit analysis
* Customer retention
* Cross-selling
* Risk monitoring
* Financial decision-making



## 🚀 Future Improvements

Potential improvements include:

* Building a customer churn prediction model.
* Developing a credit-risk prediction model.
* Creating customer lifetime value analysis.
* Applying clustering for customer segmentation.
* Building automated Power BI reports.
* Adding time-series analysis for banking trends.
* Developing predictive models using machine learning.


## ⭐ Project Highlights

**Python:** Data Cleaning + EDA + Statistical Analysis + Visualization

**Power BI:** Interactive Dashboard + Business Reporting

**Business Focus:** Customer Segmentation + Banking Behavior + Financial Insights
