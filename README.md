
# 📊 Power BI Dashboard – E-commerce Sales Analysis

## 📌 Project Overview

This project focuses on analyzing **E-commerce sales data (2021–2022)** using **Power BI**.
The goal was to uncover insights into sales performance, customer segmentation, product profitability, and regional trends.

---

## 🗂️ Dataset

* **ecommerce\_dat.csv**

  * Customer ID, Name, Category, Product, Segment, City, Country, Region, Delivery Status, Order Date, Shipping Details, Sales, Profit, Quantity, Discount, etc.
* **us\_state\_long\_lat\_code.csv**

  * State (short code), Latitude, Longitude, State Name
* **Calendar Table**

  * Date, Day, Month, Year (Jan 2021 – Dec 2022)

---

## 🔧 Data Preparation

* Cleaned data (removed duplicates, handled null values).
* Built relationships:

  * **Customer State → US States (lat/long)**
  * **Order Date → Calendar Date**
* Created calculated fields & **DAX measures**:

  * **YTD, PYTD, YOY Sales & Profit**
  * **Profit Margin Metrics**
  * **Concatenated City Names for better grouping**

---

## 📈 Dashboard Features

* **KPIs**: YTD Sales, YTD Profit, YTD Quantity, YTD Profit Margin (with YOY comparison).
* **Matrix Report**: Category-wise breakdown with YTD, PYTD, and YOY Sales.
* **Visuals & Charts**:

  * Top 5 & Bottom 5 Products by Sales
  * Sales by Region & State (Map visualization)
  * Sales by Shipping Type
  * Customer Segment filter (Consumer, Corporate, Home Office)



