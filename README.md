📊 E-Commerce Customer Segmentation using RFM Analysis
📌 Project Overview

This project focuses on analyzing customer purchasing behavior in an e-commerce business using RFM (Recency, Frequency, Monetary) analysis.
The goal is to segment customers into meaningful groups so that businesses can take data-driven marketing and retention decisions.

This is a real-world Data Analyst project involving data cleaning, feature engineering, segmentation, visualization, and business insights.

🎯 Business Problem

E-commerce companies often struggle to answer questions like:

Who are our most valuable customers?

Which customers are likely to churn?

Which customers should receive promotions?

Where does most revenue come from?

RFM analysis provides a structured way to answer these questions using transaction data.

🧠 What is RFM?

RFM stands for:

Recency (R): How recently a customer made a purchase

Frequency (F): How often a customer makes purchases

Monetary (M): How much money a customer has spent

Using these three metrics, customers are segmented into meaningful groups.

🗂️ Dataset Description

Source: Online Retail / E-commerce Transactions Dataset

Records: Customer purchase transactions

Key Columns:

InvoiceNo

CustomerID

InvoiceDate

Quantity

UnitPrice

Country

🛠️ Tools & Technologies Used

Python

Pandas & NumPy – data cleaning and analysis

Matplotlib / Seaborn – visualizations

Scikit-learn – clustering (KMeans)

Power BI / Tableau / Streamlit – dashboard creation

Jupyter Notebook

🔍 Project Workflow
1️⃣ Data Cleaning

Removed missing Customer IDs

Removed canceled transactions

Handled duplicates

Created total purchase value

2️⃣ Feature Engineering (RFM Calculation)

Recency: Days since last purchase

Frequency: Number of transactions per customer

Monetary: Total spending per customer

3️⃣ Customer Segmentation

Normalized RFM values

Applied KMeans clustering

Segmented customers into groups such as:

Champions

Loyal Customers

Potential Loyalists

At-Risk Customers

Low-Value Customers

4️⃣ Data Visualization & Dashboard

Customer segment distribution

Revenue contribution by segment

Recency vs Frequency plots

Monetary value comparison

KPI summary dashboard

📈 Key Insights

A small percentage of customers contribute the majority of revenue

Loyal and Champion customers show high frequency and high monetary value

At-risk customers have high past spending but low recent activity

Targeted campaigns can significantly improve retention and revenue

📊 Dashboard Preview

(Add screenshots here)
Example visuals:

RFM segmentation chart

Revenue by customer segment

Customer distribution heatmap

🚀 Business Recommendations

Champions: Offer exclusive rewards and early access

Loyal Customers: Upsell and cross-sell products

At-Risk Customers: Run re-engagement campaigns

Low-Value Customers: Low-cost promotions or automated emails
