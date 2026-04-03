# 🍕 Plato’s Pizza Analysis 

**Plato’s Pizza Analysis: Revenue, Sales Efficiency, and Customer Behavior Insights Dashboard**

A dynamic, interactive data visualization and statistical analysis project designed to explore a full year of pizza sales data, focusing on revenue trends, sales efficiency, peak ordering hours, order timing, weekday impact, product performance, and inventory management.

---

# 📖 Project Description

**Plato’s Pizza Analysis** is a high-performance analytical solution developed to transform over **40,000+ rows of transactional pizza sales data** into meaningful business intelligence.

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

## 📊 Daily Sales Trends (Bar Chart)

1. **Orders by Day:**
- Friday and Saturday show the highest order volumes  
- Weekday demand remains steady but comparatively lower  

## 📊 Hourly Sales Trends (heatmap)
1. **Orders by Hour:**
It answers:

- When do customers place the most orders?
- Which days are busiest?
- What are the slowest hours?

2. **Friday and Saturday**

- Show consistently high values
- Strong evening demand
- Highest overall customer traffic

3. The busiest hours occur during:
  - Lunch: **12:00–13:00**  
  - Dinner: **17:00–18:00**

4. Demand decreases around:

- **3:00 PM – 4:00 PM** - least active daytime period

5. Business Insights from This Chart

- Lunch and dinner hours represent primary revenue-generating windows.
- Weekend evenings show maximum customer demand, requiring increased staffing.
- Mid-afternoon hours represent low demand periods, suitable for reduced staffing.
- Late-night hours show minimal activity, can consider introducing "last evening" promotions to encourage customer's to place orders before 22.

---

## 🍕  Combination Chart  
Horizontal Bar Chart (Left Side)
→ Shows total revenue by pizza type
100% Stacked Bar Chart (Right Side)
→ Shows percentage distribution of pizza sizes within each pizza type

1. This chart is used to:

- Compare revenue performance across pizza types
- Understand customer size preferences within each type
- Identify best-performing pizza categories
- Support inventory and menu optimization decisions

2. Business Insights from This Chart:

- Classic pizzas are the highest revenue contributors, making them key revenue drivers.
- Large-sized pizzas dominate across most categories, indicating strong customer preference for value-sized products.
- Veggie and Chicken pizzas show particularly high Large-size demand, suggesting bulk purchase behavior.
- Regular-size Classic pizzas remain highly popular, indicating balanced size demand.

---

## 🏆 Top & Bottom Sellers (Bar Charts)

1. Displays:

- Top 5 pizzas by revenue  
- Bottom 5 pizzas by revenue  

2. Supports **Menu Engineering Decisions** such as:

- Promotion strategies  
- Product optimization  
- Menu restructuring  

---
## 🏆 Area Chart (Monthly Performance)
1. This chart higlights:

- Monthly sales and order trends
- Peak-performing/low-performing months
- Trends to understand seasonal patterns
- Patterns to forecast future demand trends

2. Business Insights from This Chart

- **July** is the peak demand month, requiring increased staffing and inventory preparation.
- **October** records the lowest performance, indicating a need for promotional campaigns.
- Mid-year months show higher demand, suggesting seasonal buying behavior.
- Late-year decline (September–October) indicates possible seasonal slowdown.
We need to focus on marketing strategy development based on seasonal demand patterns.

---
## 📌 Donut Chart used for Ingredient & Inventory Classification Analysis.
1. This chart is used to:

- Show proportion of ingredient usage types
- Compare Single-Use vs Multi-Use ingredients
- Support inventory planning
- Identify resource utilization patterns 
- Help reduce material waste and stock shortages

2. It answers:

How many ingredients are used once vs multiple times?
Which ingredient type dominates inventory usage?
How can stock planning be optimized without affecting efficiency?

3. Business Insights from This Chart

- A higher number of **Single-Use** ingredients suggests increased inventory diversity and potential storage challenges.
- **Multi-Use** ingredients improve operational efficiency, as they reduce dependency on specialized stock.
- Optimizing recipes to increase Multi-Use ingredient utilization may help reduce overall inventory costs.

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

![Dashboard Overview](https://github.com/tanya-saini/Platos_Pizza_Analysis/blob/main/dashboard%20overview.png)
![Dashboard Detailed](https://github.com/tanya-saini/Platos_Pizza_Analysis/blob/main/dashboard%20detailed.png)

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
