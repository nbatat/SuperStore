# 🛒 Global Superstore - Power BI Analytics Project

## 📌 Project Overview

This project analyzes the purchasing behavior of customers in a global store from 2011 to 2014. It uses Power BI to model and visualize patterns across different regions including LATAM, APAC, US, and Africa.

The dataset used for this project was sourced from Kaggle:  
https://www.kaggle.com/datasets/fatihilhan/global-superstore-dataset

---

## 🎯 Project Objectives

- Understand purchasing trends, product preferences, and key influencing factors.
- Detect patterns across different customer segments and regions.
- Support marketing and inventory management strategies with data-driven insights.

---

## 📊 Hypotheses

- Personalized marketing strategies based on customer behavior will significantly improve retention and sales.
- Store location impacts product preferences and sales performance, varying across global regions.

---

## 🗂️ Dataset Description

The dataset includes detailed information such as:

- Customer Information (ID, Name, Discounts, Region)
- Product Information (ID, Name, Category, Sales, Profit)
- Order Information (Order ID, Dates, Priorities, State, Region)
- Shipping Information (Shipping IDs, Costs, Dates, Modes)

Data cleaning and transformation were performed using Power BI and Excel.

---

## 🧩 Data Modeling

Relationships between tables were established following a star schema, with some bridge tables created for better organization:

- Customers ↔ Orders (One-to-Many)
- Orders ↔ Products (Many-to-Many)
- Orders ↔ Shipping (One-to-One)
- Date Period Table for time intelligence
- Calculated Measures Table for KPIs

> See ER Diagram: [View ER Diagram](https://drive.google.com/drive/u/0/folders/1n30EYYGeA_W2JDXG3bgJOJoir_QtEFZk)

---

## 📈 Power BI Visualizations

Several interactive dashboards were built using Power BI to display:

- Sales and Profit trends
- Regional sales comparison
- Customer segmentation
- Shipping performance
- Year-over-Year (YoY) and Year-To-Date (YTD) analysis

> *Screenshots and visual examples are available in the report file.*

---

## 📥 Project Files

- `Global_Superstore.pbix` → Power BI file with full project and dashboards
- `Entity_Relationship_Diagram.pdf` → Detailed schema and relationships
- `Project_Description.pdf` → Full explanation and data preparation process

---

## 📢 Contact

If you'd like to access the PBIX file, discuss this project, or collaborate, feel free to connect:

**Natalia Batet**  
[LinkedIn Profile](https://www.linkedin.com/in/natalia-batet/)

---

# Tags

`#PowerBI` `#DataAnalytics` `#Dashboard` `#GlobalStore` `#BusinessIntelligence`
