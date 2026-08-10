# 📊 Blinkit Sales and Products Analysis Dashboard

## 📌 Project Overview

This project is an interactive **Blinkit Sales & Product Analysis Dashboard** created using **Microsoft Power BI**. The aim of the project is to transform retail sales data into meaningful business insights that can support better and faster decision-making.

The dashboard brings together **sales, product, and outlet data** into a single analytical view. It focuses on analyzing sales performance, product performance, outlet performance, customer ratings, and product visibility through interactive reports and visualizations.

**Power Query** was used for data cleaning and transformation, a **Star Schema** was used for data modeling, and **DAX** measures were created for key business calculations.

---

## 🎯 Objectives

The main objectives of this project are to:

* Analyze overall retail sales performance.
* Consolidate sales, product, and outlet data into a clean data model.
* Calculate important business metrics such as Total Sales, Average Ratings, and Average Visibility.
* Identify top-performing product categories and outlet types.
* Analyze the relationship between product visibility and sales performance.
* Provide interactive filters to explore data by outlet type, outlet size, and location.

---

## 🛠️ Tools Used

* Microsoft Power BI Desktop
* Power Query Editor

Power BI was used for report design and visualization, Power Query for data transformation, DAX for KPI calculations, and the Star Schema for managing relationships between fact and dimension tables.

---

## 📂 Dataset

The dashboard uses retail sales, product, and outlet-level data.

The data model contains:

* **Fact_sales** – transactional sales records.
* **Dim_Product** – product-level information such as Item Type, Fat Content, and Visibility.
* **Dim_outlet** – outlet-level information such as Outlet Size, Location Type, and Establishment Year.

---

## 🧹 Data Cleaning

The data was prepared using **Power Query** before developing the dashboard.

The main data preparation process included:

* Data cleaning
* Data shaping
* Data transformation
* Preparing fields for analysis
* Creating a structured data model

Power Query was used as the main data preparation layer before loading the data into the Power BI model.

---

# 📊 Dashboard Overview

## Page 1 – Executive Sales Dashboard

This page provides a high-level overview of business performance and answers the question:

> **"Where is the business generating revenue from?"**

### KPI Cards

* Total Sales – **1.20M**
* Average Ratings – **3.92**
* Total Products – **2K**
* Number of Outlets – **10**
* Average Visibility – **7.02%**

### Visualizations

* Sales by Item Type
* Sales by Outlet Size
* Sales by Outlet Location Type
* Sales by Outlet Establishment Year
* Sales by Outlet Type

### Slicers

* Outlet Type
* Outlet Size
* Location Type
* Item Type

---

## Page 2 – Product Insights Dashboard

The second page focuses on deeper product-level analysis and answers the question:

> **"Why are certain sales patterns occurring?"**

### Visualizations

* Item Visibility vs Total Sales
* Revenue by Item Type
* Fat Content vs Sales
* Outlet Size vs Average Rating
* Top 10 Products by Visibility

---

## 📈 DAX Measures

The dashboard uses calculated measures for the main business KPIs:

```DAX
Total Sales

Average Ratings

Total Products

Number of Outlets

Average Visibility

Avg Sales
```

These measures are used to power the KPI cards and visualizations throughout the report.

---

## 📷 Dashboard Screenshots

### Executive Sales Dashboard

<img width="1362" height="737" alt="image" src="https://github.com/user-attachments/assets/c997bcd6-c83b-4b4d-bc9a-82c76b1f6fc3" />


### Product Insights Dashboard

<img width="1357" height="740" alt="image" src="https://github.com/user-attachments/assets/60e91a5d-b221-403e-8d5a-9fe8d19f1821" />


---

## 📁 Project Structure

```text
Blinkit-PowerBI-Dashboard/
│
├── Dashboard Screenshots/
│   ├── Executive Sales Dashboard.png
│   └── Product Insights Dashboard.png
│
├── Blinkit Dashboard.pbix
│
├── Blinkit Dashboard.pdf
│
├── Blinkit Dataset.xlsx
│
└── README.md
```

---

## 📌 Key Insights

* A small number of item categories contribute a large share of total sales.
* Outlet size and location type have a visible influence on sales performance.
* Product visibility does not have a strictly linear relationship with sales.
* Some low-visibility products still perform well, showing that factors such as pricing and category demand can also influence sales.
* Average customer ratings remain relatively consistent at around **3.9** across most outlet sizes.

---

## 💼 Skills Demonstrated

* Data Cleaning
* Power Query
* Data Transformation
* Data Modeling
* Star Schema
* DAX
* KPI Development
* Data Visualization
* Dashboard Design
* Business Intelligence
* Interactive Reporting

---

## 👨‍💻 Author

**Kartik G**

**Aspiring Data Analyst**

### Skills

* Power BI
* Power Query
* DAX
* Excel
* Python
* Pandas
* NumPy
* Data Visualization
* Data Analysis
