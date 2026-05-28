# Adidas Sales Analysis & Business Intelligence Dashboard

## 📌 Project Overview

Developed an end-to-end Sales Analytics and Business Intelligence project using Python and Power BI to analyze Adidas sales performance across multiple business dimensions. The project involved data cleaning, exploratory data analysis (EDA), trend identification, profitability analysis, and interactive dashboard development to generate actionable business insights.

The analysis focused on evaluating product performance, regional sales contribution, operating profit trends, sales channel effectiveness, and revenue distribution using data-driven visualization techniques.

# 📊 Dataset Details

* Records Analyzed: 9648
* Features: 13
* Dataset Type: Retail Sales Analytics

## Key Attributes

* Retailer & Retailer ID
* Invoice Date
* Region, State, City
* Product Category
* Units Sold
* Price per Unit
* Total Sales
* Operating Profit
* Operating Margin
* Sales Method

# 🛠️ Technologies & Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Power BI
* Jupyter Notebook

# 📂 Project Workflow-

## 🔹 Data Preprocessing

* Performed data validation and quality checks
* Verified null values and duplicate records
* Converted and formatted date columns
* Optimized data types for analysis

## 🔹 Exploratory Data Analysis (EDA)

Conducted detailed business analysis including:

* Sales trend analysis
* Product-wise revenue analysis
* Region-wise performance analysis
* Operating profit evaluation
* Sales method effectiveness analysis
* Monthly and yearly trend analysis

## 🔹 Data Visualization

Created analytical visualizations to identify:

* Revenue distribution patterns
* High-performing regions and products
* Profitability trends
* Sales growth patterns
* Business performance indicators

## 🔹 Power BI Dashboard Development

Designed interactive dashboards featuring:

* KPI Metrics
* Dynamic Filters & Slicers
* Sales Performance Monitoring
* Profitability Analysis
* Region-wise Business Insights
* Product Performance Dashboard
* Trend Analysis Reports

# 📈 Key Business Insights

* Identified high-revenue and high-profit product categories
* Analyzed regional contribution towards total sales performance
* Evaluated operating margin trends across business segments
* Compared sales performance across different sales methods
* Tracked monthly sales fluctuations and growth trends
* 
# 📊 Sample Python Analysis

```python
import pandas as pd

# Load Dataset
df = pd.read_csv("adidas_sales.csv")

# Dataset Information
print(df.info())

# Missing Value Analysis
print(df.isnull().sum())

# Product-wise Revenue
print(df.groupby('Product')['Total Sales'].sum())

# Region-wise Operating Profit
print(df.groupby('Region')['Operating Profit'].sum())
```
# 📊 Power BI Dashboard Features

* Executive KPI Dashboard
* Sales Trend Visualization
* Product Performance Analysis
* Profitability Dashboard
* Regional Sales Insights
* Interactive Business Reports
* Dynamic Data Filtering

# 🚀 Business Outcome

The project enabled comprehensive analysis of Adidas sales operations by transforming raw transactional data into interactive business intelligence dashboards, helping derive strategic insights related to revenue growth, profitability, and regional business performance.

# 👩‍💻 Author

Tanushree Kashiv
Data Analyst | Python | EDA | Power BI

