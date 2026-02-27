# FUTURE_DS1
This project demonstrates practical skills in data cleaning (Python/Pandas), exploratory data analysis, business insight generation, and dashboard development using Power BI.

# 📊 Sales Data Analytics Dashboard

## Overview
This project presents an end-to-end sales data analytics workflow using an online retail dataset (2010–2011). The objective is to analyze revenue performance, product contribution, regional sales distribution, and time-based trends. Data was loaded and processed in Python, followed by exploratory data analysis (EDA) and cleaning. An interactive Power BI dashboard was then developed to visualize key business metrics and insights.

---

## Dataset
- Online retail transactional dataset (2010–2011)
- Contains invoice details, products, quantities, prices, customers, and country information
- Includes sales and returns transactions

Key fields:
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

---

## Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook
- Power BI
- Microsoft Excel

---

## Steps Performed

### 1. Data Loading
- Imported CSV dataset into Python using Pandas
- Inspected structure and data types

### 2. Exploratory Data Analysis (EDA)
- Checked missing values
- Analyzed distributions and sales patterns
- Identified returns and anomalies

### 3. Data Cleaning
- Removed cancelled/return transactions (negative quantity)
- Handled missing descriptions and customer IDs
- Created Revenue (Sales) column  
  `Revenue = Quantity × UnitPrice`

### 4. Feature Preparation
- Extracted Year and Month from InvoiceDate
- Prepared cleaned dataset for visualization

### 5. Dashboard Development
- Imported cleaned data into Power BI
- Created KPIs and visuals:
  - Revenue over time
  - Top-selling products
  - Revenue by country
  - Monthly sales trend

---

## Dashboard
The Power BI dashboard provides an interactive view of:
- Total Revenue
- Sales Trend (2010–2011)
- Top Products by Revenue
- Regional Sales Distribution
- Seasonal Patterns

---

## Results & Insights
- A small number of products generate a large share of total revenue
- The United Kingdom accounts for the majority of sales
- Sales peak during the November–December holiday season
- Revenue increased significantly from 2010 to 2011

---

## How to Run

### Python Analysis
1. Open the Jupyter Notebook
2. Install dependencies:
   ```bash
   pip install pandas numpy
3. Run all cells to reproduce cleaning and analysis

Power BI Dashboard

Open the ONLINE SALES.pbix file in Power BI Desktop

Refresh data if needed

Explore interactive visuals
