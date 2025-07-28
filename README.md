# Adventure Works Power BI Dashboard: Global Sales & Customer Insights

An interactive and insightful Power BI dashboard built to help **Adventure Works**, a global cycling equipment manufacturer, monitor performance across regions, analyze product trends, and identify high-value customers using dynamic visualizations.

---



##  About the Project

### 🔹 Introduction
**Adventure Works** is a multinational company specializing in cycling equipment and accessories, operating across **Europe**, **North America**, and the **Pacific**. To support data-driven decision-making and streamline performance tracking, a **multi-page Power BI dashboard** was developed.

### 🔹 Objective
The primary goal of this project was to create a comprehensive and interactive dashboard that enables management to:
- Track KPIs such as **Sales**, **Revenue**, **Profit**, and **Returns**
- Compare performance across different **regions**
- Analyze **product-level** trends
- Identify and focus on **high-value customers**

---

##  Dataset Overview

- **Total Files**: 10 Excel CSV files

### 🔸 Fact Tables:
- `Sales Data`
- `Returns Data`

### 🔸 Dimension Tables:
- `Customer Lookup`
- `Calendar Lookup`
- `Product Lookup`
- `Territory Lookup`
- `Product Categories Lookup`
- `Product Subcategories Lookup`

---

##  Dashboard Design & Features

### 1. Executive Dashboard (Track KPIs)


<img width="1349" height="745" alt="Screenshot 2025-07-25 231047" src="https://github.com/user-attachments/assets/110f499e-1038-4ac5-9770-a822f54cdcd6" />

#### 🔧 Design Highlights:
The top part of the dashboard, being the most critical real estate, displays the four main KPIs using card visuals:
- **KPI Cards**: Revenue, Profit, Orders, Return Rate  
- **Line Chart**: Revenue trend over time (2020–2022)  
- **KPI Visuals**: Current month vs. previous month performance  
- **Bar Chart**: Orders by product category  
- **Matrix**: Top 10 products with Revenue & Return Rate  
- **Cards**: Most ordered & most returned product types  

####  Key Questions Answered:
- What are the current values of the main KPIs?
- How has revenue trended over time from 2020 to 2022?
- What is the performance of the current month compared to the previous month?
- How are orders distributed across different product categories?
- Which products are the top performers in terms of orders and revenue?
- Which products have the highest return rates?
- What are the most ordered and most returned product types?

---

### 2. Regional Map (Compare Regional Performance)

<img width="1292" height="722" alt="Screenshot 2025-07-25 225544" src="https://github.com/user-attachments/assets/a47f6167-51ed-451a-843f-24f6fb5c1856" />

####  Design Highlights:
- **Map Visual**: Orders by country  
- **Continent Slicers** for drill-through  

####  Key Questions Answered:
- How are orders distributed across different countries and regions?
- How does performance vary by continent?

---

### 3. Product Detail (Analyze Product-Level Trends)

<img width="1315" height="740" alt="Screenshot 2025-07-25 230015" src="https://github.com/user-attachments/assets/02117d2a-949d-4cf9-a913-db370e439b42" />

####  Design Highlights:
- **Gauge Charts**: Current month metrics vs. targets  
- **Line Chart**: Profit simulations based on cost price variation  
- **Area Chart with Field Parameters**: Trends in key metrics over time  

####  Key Questions Answered:
- How does a specific product perform in terms of orders, revenue, and profit?
- How would changes in cost prices affect profit margins?
- What are the trends for orders, revenue, profit, returns, and return rate over time?

---

### 4. Customer Detail (Identify High-Value Customers)

<img width="1326" height="743" alt="Screenshot 2025-07-25 231209" src="https://github.com/user-attachments/assets/76806df8-a2b1-40c6-bafc-75facaf7a224" />

####  Design Highlights:
- **Cards**: Total unique customers, average revenue per customer  
- **Line Chart**: Customer metrics over time  
- **Donut Charts**: Income & occupation segmentation  
- **Table**: Top 100 customers by orders and revenue  
- **Highlight Card**: Top customer by revenue  

####  Key Questions Answered:
- How many unique customers does the company have?
- What is the average revenue per customer?
- How have these metrics changed over time?
- What is the demographic composition of customers by income and occupation?
- Who are the top 100 customers by revenue and orders?
- Who is the top customer and what is their contribution to revenue?

---

##  Tools & Techniques Used

- **Power BI Desktop**
- **Power Query** for data transformations
- **DAX** for calculated columns and measures
- **Drill-through**, **field parameters**, and **numeric range slicers**
- Interactive visuals: KPI cards, bar charts, line/area charts, maps, matrix tables

---

##  Conclusion

The interactive dashboard developed for **Adventure Works** serves as a comprehensive analytical tool for management. By enabling deep dives into sales data, regional performance, product profitability, and customer value, this Power BI solution empowers stakeholders to make strategic and data-driven decisions.

