# 📊 Power BI Sales Dashboard Project

## 📌 Project Overview

This project is a **Power BI Sales Dashboard** designed to analyze business performance using interactive visuals and KPIs.
The dashboard provides insights into **sales, profit, customers, returns, and product performance**.

It also includes a **mobile-friendly layout**, making it accessible across devices.

---

## 🎯 Objectives

* To analyze overall sales performance
* To track profit and returns
* To understand customer behavior
* To compare product and region performance
* To build an interactive and user-friendly dashboard

---

## 📂 Dataset Used

The project is built using multiple datasets:

* Sales_Fact
* Customer_Dim
* Product_Dim
* Region_Dim
* Date_Dim
* Returns_Fact

---

## 🛠️ Tools & Technologies

* Power BI Desktop
* Power Query (Data Cleaning & Transformation)
* DAX (Data Analysis Expressions)

---

## 🔄 Data Preparation

* Removed blank rows
* Fixed column names
* Set correct data types
* Created relationships between tables
* Built a proper data model (Star Schema)

---

## 📊 Key Measures (DAX)

### 💰 Sales & Profit

* Total Sales
* Total Profit
* Total Orders
* Total Returns

### 👥 Customer Analysis

* Total Customers
* Returning Customers

### 📦 Product Price KPIs

* Average Product Price = AVERAGE(Product_Dim[Price])
* Highest Product Price = MAX(Product_Dim[Price])
* Lowest Product Price = MIN(Product_Dim[Price])

### ➕ Additional Measure

* Price Range = Highest Price - Lowest Price

---

## 📈 Dashboard Features

### 🔹 KPI Cards

* Total Customers
* Returning Customers
* Total Profit
* Average, Highest, Lowest Product Price

---

### 🔹 Charts Used

#### 📊 Stacked Bar Chart

* Shows **Sales vs Returns by Product**

#### 🍩 Donut Chart

* Displays **Category-wise Sales Distribution**

#### 📉 Line Chart

* Shows **Monthly Sales Trend**

#### 📋 Table Visual

* Displays:

  * Product Name
  * Total Profit
  * Total Orders
  * Total Sales
  * Total Returns

---

### 🌍 Region Analysis

* Region-wise performance comparison
* Interactive region selection (East, West, North, South)

---

## 📱 Mobile Layout

* Designed a separate **mobile view**
* Optimized visuals for small screens
* Ensured better readability and user experience

---

## 🎨 Dashboard Design

* Clean and minimal UI
* Dark theme for better visibility
* Proper alignment and spacing
* Consistent color usage

---

## 💡 Insights Generated

* Identified top-performing products
* Compared sales vs returns
* Analyzed customer behavior
* Found pricing distribution trends

---

## 🚀 Conclusion

This dashboard helps in making **data-driven decisions** by providing clear insights into sales, profit, and customer trends.
The use of KPIs, charts, and mobile layout makes it **interactive and user-friendly**.

---


---
"# Power-BI-Final-Project" 
