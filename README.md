**INTERN ID : CITS4956 
FULL NAME : TANVI SUDESH LAD 
NO. OF WEEKS : 04 
PROJECT NAME : SALES TREND VISUALIZATION** 
**PROJECT SCOPE : Add real-time data and sales forecasting.
                Integrate ML for automated trend prediction.
                Connect live database with AI-powered insights.**


# Superstore Sales Trend Visualization - Power BI Dashboard

## 📊 Project Overview
This project analyzes 4 years of Superstore sales data using Power BI to identify sales trends, top performing regions, categories, and customer segments. 
The goal is to help business leaders make data-driven decisions for revenue growth and profitability.

**Dataset**: Superstore_Cleaned.xlsx 
**Tool**: Microsoft Power BI Desktop
**Time Period**: 2014 - 2017

## 📈 Key Metrics
| Metric | Value |
| --- | --- |
| **Total Sales** | 733.22K |
| **Total Profit** | 93.44K |
| **Total Orders** | 2K |
| **Profit Margin** | 12.74% |

## 📊 Dashboard Features

### 1. **KPI Cards**
Shows overall business performance at a glance: Total Sales, Total Profit, Total Orders, Profit Margin %

### 2. **Total Sales by Month**
Line chart showing monthly seasonality. Peak sales observed in April and August.

### 3. **Total Sales by Category and Region**
Stacked bar chart. `Technology` in `West` region is the top performer with 0.10M sales.

### 4. **Total Sales and Profit by Segment**
Bar chart. `Consumer` segment drives 53% of total sales = 0.33M

### 5. **Total Sales by State**
Filled map to visualize geographical distribution of sales across US.

### 6. **Interactive Slicers**
Filter dashboard by `Year`, `Ship Mode`, and `Category` for drill-down analysis.

## 🔍 Key Insights
1. **Seasonality**: Sales peak in April and August. Q4 marketing should be increased.
2. **Top Performer**: Technology category in West region generates highest revenue.
3. **Customer Focus**: Consumer segment contributes the most to sales. Targeted campaigns recommended.
4. **Profitability**: Overall profit margin is healthy at 12.74%.

## 💡 Business Recommendations
1. Increase inventory and marketing budget before April and August peak months.
2. Expand Technology product line in West and Central regions.
3. Launch loyalty programs for Consumer segment to increase repeat orders.
4. Review Furniture category profit to improve margins.

## 🛠 Tools & Techniques Used
- **Power BI**: Data Modeling, DAX Measures, Data Visualization
- **DAX Measures Created**:
  ```DAX
  Total Sales = SUM('Superstore_Cleaned'[Sales])
  Total Profit = SUM('Superstore_Cleaned'[Profit])
  Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
  Total Orders = DISTINCTCOUNT('Superstore_Cleaned'[Order ID])


  📁 Project Files
├── Dashboard.pbix # Power BI Dashboard File
├── Superstore_Data.xlsx 
├── Notebook
└── README.md # Project Documentation


🚀 How to Run
Download and install Microsoft Power BI Desktop.
Open Superstore_Sales_Dashboard.pbix file.
Click Refresh to load latest data.
Use slicers to filter and explore insights.
