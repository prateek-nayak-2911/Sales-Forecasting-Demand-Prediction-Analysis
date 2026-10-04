# 📊 Sales Forecasting & Demand Prediction Analysis

A data analytics project focused on analyzing historical retail sales, identifying demand patterns and seasonality, and forecasting future sales using the **Walmart M5 Forecasting Dataset**.

The project uses **SQL for data preparation and analysis** and **Power BI for interactive visualization and dashboarding**.

---

## 🎯 Project Objective

The main objective of this project is to understand how historical sales data can be used to identify trends, seasonal patterns, peak demand periods, and future sales opportunities.

The analysis aims to help a retail business improve:

* Sales planning
* Demand forecasting
* Inventory management
* Product planning
* Business decision-making

---

## 📌 Business Problem

The retail company is facing challenges such as:

* Sudden increases or decreases in product demand
* Difficulty in predicting future sales
* Inefficient inventory planning
* Seasonal fluctuations in demand
* Lack of clear sales performance insights

This project analyzes historical sales data to identify these patterns and provide data-driven recommendations.

---

## 🗂️ Dataset

### Walmart M5 Forecasting Dataset

The project uses the **Walmart M5 Forecasting Dataset**, which contains historical daily sales data for products across multiple Walmart stores.

### Dataset Files Used

* `sales_train_evaluation.csv` — Historical daily unit sales
* `calendar.csv` — Date, weekday, month, year, events and SNAP information
* `sell_prices.csv` — Product prices by store and week

The `sample_submission.csv` file is not required for this project.

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                                    |
| --------------- | ------------------------------------------ |
| **SQL / MySQL** | Data cleaning, transformation and analysis |
| **Power BI**    | Interactive dashboard                      |
| **Excel**       | Supporting data inspection                 |
| **GitHub**      | Project documentation and version control  |

---

## 🔄 Project Workflow

```text
Walmart M5 Dataset
        ↓
Data Understanding
        ↓
Data Cleaning & Preprocessing
        ↓
Wide → Long Data Transformation
        ↓
SQL Database
        ↓
Exploratory Data Analysis
        ↓
Trend & Seasonal Analysis
        ↓
Demand Analysis
        ↓
Sales Forecasting
        ↓
Power BI Dashboard
        ↓
Business Insights & Recommendations
```

---

## 🧹 Data Cleaning & Preparation

The following preprocessing steps are performed:

* Handling missing values
* Checking duplicate records
* Converting date information
* Transforming sales data from wide format to long format
* Joining sales data with calendar information
* Joining product prices with sales data
* Creating useful time-based columns
* Validating sales and price values

### Final Analytical Structure

The transformed data follows a structure similar to:

```text
Date
Item_ID
Department
Category
Store_ID
State
Units_Sold
Selling_Price
Sales
Year
Month
Week
Weekday
```

---

## 📊 SQL Analysis

SQL is used to answer important business questions and generate analytical datasets/views.

### Key Analysis

* Total Units Sold
* Total Sales
* Monthly Sales Trends
* Weekly Sales Trends
* Yearly Sales Trends
* Category-wise Performance
* Department-wise Performance
* Store-wise Performance
* Product-wise Demand
* Top 10 Products
* Peak Sales Periods
* Seasonal Demand Patterns
* Sales Growth Analysis
* Moving Average
* High-Demand Products
* Low-Demand Products

---

## 📈 Forecasting

A basic trend-based forecasting approach is used to estimate future sales and demand.

The forecasting analysis focuses on:

* Historical sales trends
* Monthly demand patterns
* Seasonal behavior
* Recent sales performance
* Moving averages
* Product demand trends

The objective is to provide an understandable forecasting approach suitable for business decision-making.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of sales performance and demand trends.

<img width="1037" height="587" alt="image" src="https://github.com/user-attachments/assets/48b41f38-b801-40db-803a-21d2231c96eb" />


### Dashboard Includes

**KPI Cards**

* Total Sales
* Total Units Sold
* Total Products
* Average Sales

**Visualizations**

* 📈 Monthly Sales Trend
* 📊 Category-wise Sales
* 🏆 Top Products
* 🏪 Store-wise Performance
* 📅 Seasonal Sales Pattern
* 🔮 Actual vs Forecasted Sales
* 📦 Product Demand Analysis

### Filters

Users can interact with the dashboard using filters such as:

* Year
* Month
* Category
* Department
* Store
* State
* Product

---

## ❓ Business Questions

The project answers the following questions:

### 1. Which months have the highest sales?

Identifies peak sales periods and helps businesses prepare inventory in advance.

### 2. Is there a seasonal pattern in sales?

Analyzes whether demand changes during specific months, weeks or events.

### 3. What is the overall sales trend?

Determines whether sales are increasing, decreasing or remaining relatively stable.

### 4. Which products are expected to have high future demand?

Identifies products with consistently strong or increasing demand.

### 5. How can the company improve demand planning?

Provides recommendations based on historical sales, seasonality and demand patterns.

---

## 💡 Business Recommendations

Based on the analysis, the company can:

* Maintain higher inventory before peak demand periods
* Monitor low-performing products
* Use historical demand to improve stock planning
* Identify products with consistently high demand
* Adjust inventory based on seasonal patterns
* Monitor sudden changes in demand
* Use sales forecasts for better purchasing decisions

---

## 📁 Project Structure

```text
Sales-Forecasting-Demand-Prediction/
│
├── Dataset/
│   ├── calendar.csv
│   ├── sales_train_evaluation.csv
│   └── sell_prices.csv
│
├── SQL/
│   ├── database_schema.sql
│   ├── data_cleaning.sql
│   ├── sales_analysis.sql
│   └── forecasting_analysis.sql
│
├── PowerBI/
│   └── Sales_Forecasting_Dashboard.pbix
│
├── Documentation/
│   ├── Project_Report.pdf
│   └── Insights_and_Recommendations.pdf
│
└── README.md
```

---

## 🚀 Key Skills Demonstrated

* SQL Data Analysis
* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Time Series Analysis
* Sales Trend Analysis
* Demand Analysis
* Forecasting
* Power BI Dashboard Development
* Business Intelligence
* Data-Driven Decision Making

---

## 📌 Project Outcome

This project demonstrates how historical retail sales data can be transformed into meaningful business insights using **SQL and Power BI**.

The analysis helps identify sales trends, seasonal demand, high-performing products, and future demand patterns, enabling better **inventory management, sales planning and business decision-making**.

---

## 👨‍💻 Author

**Prateek Nayak**

B.Tech CSE (Data Science) Student
Interested in **Data Analytics, Business Intelligence & Data Science**

---

## ⭐ Acknowledgement

Dataset: **Walmart M5 Forecasting Dataset**

This project was developed as part of a practical Data Analytics training/project under the guidance of **Mentor Tarun Kumar**.
