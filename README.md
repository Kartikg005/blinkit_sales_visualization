# 📊 Blinkit Sales Analysis Dashboard Using Power BI

## 📌 Project Overview

This project is an interactive **Blinkit Sales Analysis Dashboard** created using **Microsoft Power BI**. The aim of the project is to transform raw sales data into meaningful business insights that can support better decision-making.

The dashboard focuses on analyzing sales performance, outlet performance, customer ratings, product visibility, and revenue distribution through interactive reports and visualizations. Power Query was used for data cleaning, and DAX measures were created to calculate important business metrics.

---

## 🎯 Objectives

The main objectives of this project are to:

* Analyze overall sales performance.
* Compare the performance of different outlet types and locations.
* Identify top-performing product categories.
* Study customer ratings and product visibility.
* Build an interactive dashboard that allows users to filter and explore data easily.

---

## 🛠️ Tools Used

* Microsoft Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)

---

## 📂 Dataset

The dataset used for this project was downloaded from Kaggle.

**Dataset Source:**
https://www.kaggle.com/datasets/architgoel29/blinkit-dashboard

---

## 🧹 Data Cleaning

Before creating the dashboard, the dataset was cleaned using Power Query. The following steps were performed:

* Corrected data types
* Standardized inconsistent values
* Handled missing values
* Replaced invalid visibility values
* Removed duplicate records
* Renamed columns for better readability

These steps ensured the dataset was accurate and ready for analysis.

---

# 📊 Dashboard Overview

## Page 1 – Executive Sales Dashboard

This page provides a high-level overview of Blinkit's business performance.

### KPI Cards

* Total Sales
* Average Rating
* Total Products
* Number of Outlets
* Average Item Visibility

### Visualizations

* Sales by Outlet Type
* Sales by Item Type
* Sales by Outlet Size
* Sales by Outlet Location Type
* Outlet Establishment Year vs Sales

### Slicers

* Outlet Size
* Outlet Type
* Item Fat Content
* Outlet Location
* Item Type

---

## Page 2 – Product Insights Dashboard

The second page focuses on product performance and customer insights.

### KPI Cards

* Total Sales
* Average Rating
* Total Products
* Number of Outlets
* Average Item Visibility

### Visualizations

* Item Visibility vs Sales
* Top 10 Products by Visibility
* Revenue by Item Type
* Average Rating by Item Type
* Fat Content vs Sales
* Outlet Size vs Average Rating

---

## 📈 DAX Measures

The following DAX measures were used in the dashboard:

```DAX
Total Sales = SUM('BlinkIT'[Sales])

Average Rating = AVERAGE('BlinkIT'[Rating])

Average Visibility = AVERAGE('BlinkIT'[Item Visibility])

Total Products = DISTINCTCOUNT('BlinkIT'[Item Identifier])

Total Outlets = DISTINCTCOUNT('BlinkIT'[Outlet Identifier])

Average Sales = AVERAGE('BlinkIT'[Sales])

Revenue % =
DIVIDE(
    [Total Sales],
    CALCULATE([Total Sales], ALL('BlinkIT'))
)
```

---

## 📷 Dashboard Screenshots

### Executive Sales Dashboard

<img width="1136" height="693" alt="image" src="https://github.com/user-attachments/assets/0ae1cd41-14cd-4276-8cb5-75522c5eb99b" />


### Product Insights Dashboard

<img width="1455" height="801" alt="image" src="https://github.com/user-attachments/assets/551c3f98-69f4-4c7a-9b49-b9895b741a05" />


---

## 📁 Project Structure

```text
Blinkit-PowerBI-Dashboard/
│
├── Blinkit Dashboard.pbix
├── Blinkit Dataset.xlsx
├── Dashboard Screenshots/
│   ├── Executive Sales Dashboard.png
│   └── Product Insights Dashboard.png
└── README.md
```

---

## 📌 Key Insights

* Compared sales across different outlet types and locations.
* Identified the best-performing product categories.
* Analyzed customer ratings to understand product satisfaction.
* Studied the relationship between product visibility and sales.
* Built an interactive dashboard with slicers for better data exploration.

---

## 💼 Skills Demonstrated

* Data Cleaning
* Power Query
* Data Modeling
* DAX
* KPI Development
* Data Visualization
* Dashboard Design
* Business Intelligence

---

## 🚀 Future Improvements

Some features that can be added in future versions include:

* Sales forecasting
* Monthly and yearly trend analysis
* Customer segmentation
* Publishing the dashboard to Power BI Service
* Row-Level Security (RLS)

---

## 👨‍💻 Author

**Kartik G**

Aspiring Data Analyst

### Skills

* Power BI
* Excel
* SQL
* Python
* Pandas
* NumPy

If you like this project, feel free to ⭐ the repository.
