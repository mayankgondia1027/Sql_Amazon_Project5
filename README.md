<img width="1024" height="373" alt="Amazon-Logo-White-PNG-Image" src="https://github.com/user-attachments/assets/ca5a2a5a-f1cc-461a-a53d-85d3230bce2a" />

🛒 Amazon Sales Analysis – Advanced SQL Project
📘 Overview

An Amazon-style e-commerce database built using SQL and CSV data to generate business intelligence insights on customers, products, sellers, and orders.

🧩 Schema

Tables: customers, sellers, category, products, orders, order_items, payments, shippings, inventory

Relations: customers → orders → items/payments; products → categories/sellers; inventory & shipping track stock and delivery

⚙️ Tech Stack

SQL (PostgreSQL/MySQL)

Power BI / Tableau (optional)

Stored procedure for real-time inventory updates

📊 Key Insights

🏆 Top Products & Categories: Revenue & contribution analysis

💎 Customer Metrics: CLTV, AOV, segmentation (new vs returning)

🧾 Seller Performance: Top sellers, inactive sellers

🚚 Shipping & Payment: Delay detection, success rate

📉 Profitability: Product margin, YoY revenue decline

🚨 Inventory Alerts: Low-stock notifications

🧠 SQL Highlights

CTEs, Window Functions (RANK, LAG), Aggregations, Subqueries, CASE logic, Stored Procedures

📈 Output

Delivers actionable insights for marketing, logistics, inventory, and customer retention.

📂 Structure
📦 amazon-sql-project
├── AMAZON.sql
├── data/
├── ER_Diagram.png
└── README.md

🚀 Summary

A compact end-to-end SQL analytics project showcasing advanced querying, data modeling, and automation — perfect for a data analyst or BI portfolio.
