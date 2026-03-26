# 🍕 Plato’s Pizza Analysis 

**Plato’s Pizza Analysis: Revenue, Sales Efficiency, and Customer Behavior Insights Dashboard**

A dynamic, interactive data visualization and statistical analysis project designed to explore a full year of pizza sales data, focusing on revenue trends, sales efficiency, peak ordering hours, order timing, weekday impact, product performance, and inventory management.

---

# 📖 Project Description

**Plato’s Pizza Analysis** is a high-performance analytical solution developed to transform over **20,000+ rows of transactional pizza sales data** into meaningful business intelligence.

The project integrates statistical analysis, visualization, and operational insights to support business decision-making, particularly around **staffing optimization, late-night operations, menu engineering, and inventory planning**.

The dashboard enables stakeholders to identify **peak demand periods**, evaluate **customer purchasing behavior**, and estimate the **opportunity cost of weekday late-night closures**, ensuring cost-effective operations.

---

# 🎯 Business Objectives

The project addresses the following analytical questions:

- How much total revenue was generated during the year?
- Can seasonality patterns be identified in sales performance?
- What is the total number of pizzas sold and total number of orders placed?
- How are sales distributed across pizza categories, sizes, and types?
- How do sales trends vary across days and months?
- Which pizzas generate the highest and lowest revenue?
- What is the Average Order Value (AOV) and Average Pizzas per Order?
- How many customers place orders each day, and are there peak hours?
- How many pizzas are typically included in each order?
- Which pizzas consistently perform as bestsellers?

---

# 🛠️ Tech Stack

The analysis was performed using a combination of modern data analytics and visualization tools:

## 📗 Microsoft Excel
Used as the primary data integration layer to merge multiple datasets into a single structured flat file. Excel supported data validation, preprocessing, and formatting prior to analysis.

## 🪐 Jupyter Notebook (Python)
Served as the primary environment for **Exploratory Data Analysis (EDA)**.

**Python Libraries Used:**
- Pandas – Data cleaning and transformation  
- NumPy – Numerical processing  
- Matplotlib – Visualization creation  
- Seaborn – Statistical plotting  

## 🧠 DAX (Data Analysis Expressions)
Used to create dynamic measures including:

- Revenue calculations  
- Average Order Value (AOV)  
- Late-night revenue loss calculations  
- Percentage weekday revenue impact  

## 📊 Power BI Desktop
Primary visualization tool used to build interactive dashboards and enable filtering across multiple dimensions. Used KPI's(Key Performance Indicators) to highlight the overall status of the business in a summarized format.

---

# 📂 Data Source

**Source:** Internal transactional pizza sales dataset.

The dataset contains detailed order-level information including:

- `order_id` – Unique order identifier  
- `pizza_id` – Unique pizza identifier  
- `quantity` – Number of pizzas ordered  
- `order_date` – Date of order  
- `order_time` – Time of order  
- `unit_price` – Price per pizza  

**Pizza Categories:**
- Classic  
- Veggie  
- Supreme  
- Chicken  

**Pizza Sizes:**
- Small (S)  
- Medium (M)  
- Large (L)  
- Extra Large (XL)  
- Double Extra Large (XXL)  

The dataset spans a **full calendar year**, enabling accurate seasonal and behavioral analysis.

---

# ⭐ Features / Highlights

## 🧩 Business Problem

The client faced challenges in balancing **labor costs** with **late-night operational revenue**, particularly during weekdays.

Key concerns included:

- Determining whether staying open **past 10:00 PM (Sunday–Thursday)** was financially viable  
- Identifying **peak demand hours**  
- Understanding which pizza categories contributed the most revenue  
- Improving **inventory planning**  
- Reducing **operational waste**

---

## 🎯 Goal of the Dashboard

The dashboard was designed to:

- Calculate revenue impact of late-night weekday operations  
- Identify peak order hours for staffing optimization  
- Segment sales by category and size  
- Highlight top and bottom performing pizzas  
- Improve operational efficiency and profitability  
- Enable data-driven decision-making  

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|-----|------|
| **Total Revenue** | **$817,860** |
| **Average Order Value (AOV)** | **$38.31** |
| **Total Pizzas Sold** | **49,574** |
| **Total Orders** | **21,350** |
| **Average Pizzas Per Order** | **2.32** |

---

# 📈 Dashboard Visualizations

## 📊 Daily & Hourly Sales Trends (Bar Chart & Heatmap)

**Orders by Day:**
- Friday and Saturday show the highest order volumes  
- Weekday demand remains steady but comparatively lower  

**Orders by Hour:**
- Peak demand occurs during:
  - Lunch: **12:00–13:00**  
  - Dinner: **17:00–18:00**

These time windows represent **critical staffing periods**.

---

## 🍕 Sales by Pizza Category (Donut Chart)

Displays distribution across:

- Classic  
- Supreme  
- Chicken  
- Veggie  

**Insights:**
- Classic pizzas dominate total order volume  
- Chicken pizzas contribute higher revenue margins  

---

## 🏆 Top & Bottom Sellers (Bar Charts)

Displays:

- Top 5 pizzas by revenue  
- Bottom 5 pizzas by revenue  

Supports **Menu Engineering Decisions** such as:

- Promotion strategies  
- Product optimization  
- Menu restructuring  

---

## 📏 Size Distribution (Stacked Bar / Pie Chart)

Breakdown of:

- Small  
- Medium  
- Large  

**Insight:**
Large pizzas generate the highest percentage of revenue, indicating strong consumer preference.

---

# 📌 Business Impact & Insights

## ⚙️ Operational Efficiency

Late-night weekday operations contribute minimal revenue.

**Impact:**
Reducing late-night weekday hours can lower operational costs without major revenue loss.

---

## 👥 Staffing Optimization

Demand patterns show:

- Low Demand: **15:00–16:00**  (realatively)
- Peak Demand: **18:00 Dinner Rush**

**Impact:**
Optimizes staffing allocation.

---

## 📦 Inventory Precision

High demand observed for:

- Large pizzas  
- Classic category  

**Impact:**
Improves procurement planning and reduces waste.

---

# 📣 Marketing Optimization Insights

## 🚀 Promote High-Revenue Pizzas
Focus promotions on top-performing pizzas to increase revenue.

## ⏰ Leverage Peak Sales Periods
Increase staffing and inventory during peak demand periods.

## 🧺 Encourage Larger Orders
Introduce combo deals and bundles to increase AOV.

---

# 📷 Glimpses of the Dashboard
![Alt text].(https://github.com/tanya-saini/Platos_Pizza_Analysis/assets/image.png)
![Dashboard Overview].(https://github.com/tanya-saini/Platos_Pizza_Analysis/blob/main/dashboard%20overview.png).

---

# 📊 Analytical Summary

The Plato’s Pizza dashboard integrates transactional and behavioral data into a unified analytical system. By combining visualization, statistical modeling, and KPI tracking, the system provides valuable insights into customer demand and product-level performance.

The analysis confirms that **weekend demand**, **dinner-hour traffic**, and **large-sized pizzas** are major contributors to revenue. Low late-night weekday revenue highlights opportunities for operational cost reduction.

Overall, the dashboard enhances decision-making across marketing, staffing, inventory, and operations.

---


# 🌍 Future Work / Project Scope

Future expansion possibilities include:
- Profitability Analysis: Ingredient costs, Labor costs, Profit margins
- Multi-store analytics  
- Franchise-level comparisons   
- Supply chain optimization  
- Automated inventory management  
- Cloud-based dashboard deployment   

---
