# 🛒 Blinkit Data Analysis Project

## 📌 Project Overview
This project focuses on analyzing Blinkit sales data to uncover key business insights. The analysis helps understand sales performance, customer preferences, and outlet-level trends using Python.

---

## 🎯 Objectives
- Analyze total and average sales performance
- Understand the impact of item fat content on sales
- Identify top-performing item types
- Compare sales across outlet sizes and locations
- Study sales trends over outlet establishment years

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset Information
The dataset contains **8,523 records** with the following key features:
- Item Type
- Item Fat Content
- Outlet Location Type
- Outlet Size
- Sales
- Rating

---

## 🧹 Data Cleaning
- Standardized inconsistent values in *Item Fat Content* (e.g., LF → Low Fat)
- Checked missing values and data types
- Ensured data consistency for analysis

---

## 📊 Key Performance Indicators (KPIs)
- **Total Sales:** $1,201,681  
- **Average Sales:** $141  
- **Total Unique Items:** 1,559  
- **Average Rating:** 4.0  

---

## 📈 Analysis & Visualizations

### 1. Total Sales by Fat Content
- Compared Low Fat vs Regular items
- Low Fat products contribute higher sales

### 2. Sales by Item Type
- Identified which product categories perform best

### 3. Sales by Outlet Location
- Tier-wise comparison of sales performance

### 4. Sales by Outlet Size
- Analyzed how outlet size affects revenue

### 5. Sales Trend by Establishment Year
- Observed how older/newer outlets perform over time

---

## 📷 Sample Visualizations
(All charts are available in the repository)
- Donut Chart (Fat Content Sales)
- Bar Chart (Item Type Sales)
- Line Chart (Yearly Sales Trend)
- Funnel Chart (Location-based Sales)

---

## 📁 Project Structure
Blinkit-Data-Analysis/
│
├── blinkit_analysis.py
├── blinkit_data.csv
├── total_sales_by_fat_content.png
├── total_sales_by_item_type.png
├── grouped_fat_sales_by_city_tier.png
├── total_sales_by_establishment_year.png
├── sales_by_outlet_size_donut.png
├── sales_by_location_funnel.png
└── README.md

---

## 🚀 Key Insights
- Low Fat products generate more revenue than Regular products
- Certain item categories dominate sales performance
- Tier 1 locations show strong sales contribution
- Medium-sized outlets contribute significantly to total sales

---

## 💼 Use Case
This project demonstrates skills in:
- Data Cleaning
- Data Analysis
- Data Visualization
- Business Insight Generation

---

## 🙋‍♀️ Author
Mounika peddapoondra

Aspiring Data Analyst with experience in Python, SQL, and Power BI.

---

## ⭐ Future Improvements
- Build an interactive dashboard in Power BI
- Add predictive analysis (sales forecasting)
- Deploy project using Streamlit
