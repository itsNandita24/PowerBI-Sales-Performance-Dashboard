# PowerBI-Sales-Performance-Dashboard
Interactive Power BI Sales Performance Dashboard using DAX, data modeling, KPIs, and interactive visualizations.
# 📊 Power BI Sales Performance Dashboard

## 📌 Project Overview

This project is an interactive **Sales Performance Dashboard developed using Microsoft Power BI** to analyze sales, orders, customers, salespeople, and city-wise performance.

The dashboard helps transform sales data into meaningful business insights through **KPIs, interactive slicers, charts, DAX measures, and data modeling**.

## 🛠️ Tools & Technologies

* Microsoft Power BI
* DAX
* SQL
* Advanced Excel
* Data Modeling
* Data Visualization

## 📂 Dataset

The project uses three tables:

### 1. Salespeople

* Snum
* Sname
* City
* Comm

### 2. Customers

* Cnum
* Cname
* City
* Snum

### 3. Orders

* Onum
* Odate
* Amount
* Cnum
* Snum

## 🔗 Data Model

The relationships used in the project are:

**Salespeople → Customers → Orders**

* Salespeople[Snum] → Customers[Snum]
* Customers[Cnum] → Orders[Cnum]

## 📊 Key KPIs

* Total Sales
* Total Orders
* Total Customers
* Total Salespeople
* Average Order Value

## 📈 Dashboard Visuals

* Monthly Sales Trend
* City-wise Sales
* Salesperson-wise Sales
* Customer-wise Orders
* Top 5 Salespeople
* Monthly Order Trend
* Sales Transaction Details

## 🎛️ Interactive Filters

The dashboard includes slicers for:

* Date
* City
* Salesperson
* Customer

## 🧮 DAX Measures

```DAX
Total Sales = SUM(Orders[Amount])

Total Orders = COUNTROWS(Orders)

Total Customers = DISTINCTCOUNT(Customers[Cnum])

Total Salespeople = DISTINCTCOUNT(Salespeople[Snum])

Average Order Value =
DIVIDE([Total Sales], [Total Orders])
```

## 🎯 Project Objective

The objective of this project is to analyze sales performance and create an interactive business dashboard that helps users understand sales trends, customer activity, salesperson performance, and city-wise sales.

## 📸 Dashboard Preview

Add your dashboard screenshot here:

`Screenshots/Sales_Dashboard.png`

## 💡 Key Learning

Through this project, I strengthened my skills in:

* Data modeling
* DAX measures
* Interactive dashboard development
* KPI creation
* Data visualization
* Business-oriented data analysis

## 👩‍💻 Author

**Nandita Maharana**

Aspiring Data Analyst | Power BI | SQL | Advanced Excel
