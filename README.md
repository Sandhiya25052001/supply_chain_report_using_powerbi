# 📦 Supply Chain Dashboard - Power BI Project

This Power BI project delivers a dynamic and insightful supply chain report. It helps visualize key operational metrics like cost, revenue, stock levels, defect rates, lead times, and supplier performance.

---
## 📌 Overview

This Power BI project focuses on analyzing end-to-end supply chain data using a unified dataset. The primary objective is to:

•Visualize critical KPIs such as cost, revenue, lead time, stock levels, and defect rates.

•Identify patterns in supplier performance and transportation effectiveness.

•Reveal how customer demographics and product types affect revenue.

•Uncover optimization opportunities for delivery timelines and inventory management.

•The dashboard is structured with easy navigation and clean design, divided into three key pages: Overview, Product Insight, and Supplier Analysis.

---
## 📊 Features of the Dataset

The dataset includes a single flat table supply_chain_data which contains:

| Feature               | Description                                                   |
| --------------------- | ------------------------------------------------------------- |
| **Product Information**  | SKU, Product Type, Price, Units Sold, Availability            |
|**Supplier Details**      | Supplier ID, Profit Margin, Defect Rate, Lead Time            |
|**Transportation Data**   | Mode of Transport, Shipping Cost, Defect Rate by Mode         |
| **Customer Demographics** | Gender-based segmentation (Male, Female, Unknown)             |
| **Location Data**        | City-based sales performance                                  |
| **Operational Metric**  | Manufacturing Cost, Order Quantity, Stock, Satisfaction Score |


This dataset serves as the foundation for all dashboard visuals and analysis.
---
## 🛠 Tools Used

•Power BI Desktop – for building the report

•Power Query – to clean and transform raw data

•DAX (Data Analysis Expressions) – to create calculated columns and KPIs

•MS Excel – used initially to shape and prepare the dataset

•GitHub – for hosting and documenting the project

---
## 📈 Dashboard Overview

### 1. **Overview Page**

•High-level KPIs: Total Revenue, Cost, Profit, Units Sold

•Revenue breakdown by Customer Gender and Product Type

•Defect rate and revenue comparison by SKU and Carrier

•Visuals: KPI Cards, Donut Chart, Bar Graph, Pie Chart


🔹 **2. Product Insight Page**

•Lead time and availability analysis by SKU

•Profit margin across product categories

•Price vs. Units Sold scatter plot for identifying high performers

•Stock vs. Order Quantity to analyze product demand


### 3. **Supplier Analysis**

•Supplier-wise average profit margin and defect rate

•Comparison of transportation modes (cost vs. quality)

•Scatter plot: Supplier performance vs. defect rate

•Insights on supplier optimization and logistics planning

---
## 🗃 Data Source

•Simulated sample dataset for academic and project use

•Dataset includes no sensitive or proprietary business data

•Structured as a single flat table to keep the model simple and efficient

---
## 📁 Project Structure

supply-chain-dashboard/

├── images/

│ ├── overview.png

│ ├── product_insight.png

│ ├── supplier_analysis.png

│ 

├── README.md

└── table_list.csv)

## 🔧 Requirements

•Which supplier provides the best balance between profit margin and defect rate?

•What product category has the highest defect percentage and how does it impact profitability?

•How do different transportation modes affect overall supply chain cost and quality?

•What is the relationship between stock levels and order quantities across SKUs?

•Which SKUs contribute the most to revenue despite having longer lead times?

•Are there any visible trends in customer demographics affecting product preferences?

•How do lead times vary by supplier and what can be done to optimize them?

•What recommendations can be drawn to improve cost efficiency and product quality across the supply chain?

---

## 🔄 Steps to Meet Requirements

•Data Profiling: Reviewed fields and data types in the dataset to identify key metrics and dimensions.

•Data Cleaning: Handled missing values, removed inconsistencies, and standardized column formats.

•Data Transformation: Used Power Query to reshape and enrich the data, such as creating calculated defect percentages.

•DAX Measures: Developed key metrics including:

•Total Revenue = SUM(Revenue)

•Profit = Revenue - Cost

•Defect Rate % = (Defects / Units Sold) * 100

•Avg Margin % = AVERAGE(Profit Margin)

•Dashboard Design: Created three interactive pages with consistent design language and slicers for filters.

•Business Insight Extraction: Interpreted visuals to answer requirement questions, and generate strategic suggestions.

---
## 📑 Report

✅ **Key Insights**

•Skincare is the most profitable product category.

•Haircare has the highest defect rate (~36.86%) and needs urgent quality control.

•Supplier 3 offers the highest average profit margin with relatively low defect rates.

•Road transport has the highest cost and defect rate, while Air is efficient but costly.

•Female customers contribute the highest percentage of revenue (~30%).

•City-level revenue shows regional performance gaps that could inform distribution strategy.

•Lead times vary significantly between suppliers; opportunities exist for delivery process optimization.

---
### Visual Examples:
- ![Overview](images/overview.png)
- ![Product Insight](images/product_insight.png)
- ![Supplier Analysis](images/supplier_analysis.png)

---

## ⚠️ Notes

- `.pbix` file is **not included** due to licensing/account restrictions.
- If you'd like a walkthrough of the report or dataset, feel free to reach out.

---

## ⭐ Credits

Created by [Sandhiya P]  
For more projects like this, check out my [GitHub Profile](https://github.com/Sandhiya25052001)
---
