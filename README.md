# Crunchy Corner QSR Financial & Operational Analysis | Power BI Dashboard

## 📌 Overview  
This project involves analyzing the financial performance, budgeting efficiency, and product-level contribution for Crunchy Corner — one of India’s largest fast food restaurant chains. The goal was to identify key drivers of profitability, optimize budget allocation, and uncover SKU-level insights using a dynamic Power BI dashboard.

Live Dashboard - https://app.powerbi.com/links/pEBuPaRpvj?ctid=dba738f5-614b-48bf-af08-525b5cba2b1e&pbi_source=linkShare
---

## 📋 Table of Contents  
- [Overview](#-overview)  
- [Project Description](#-project-description)  
- [Data](#-data)  
- [Methodology](#-methodology)  
- [Analysis and Findings](#-analysis-and-findings)  
- [Recommendations](#-recommendations)  
- [Ad Hoc Requests](#-ad-hoc-requests)  
- [Files and Resources](#-files-and-resources)  
- [Conclusion](#-conclusion)  
- [Contact Information](#-contact-information)

---

## 📂 Project Description  

### Background  
Crunchy Corner operates over 1000 fast food outlets across India and owns the highest SKU count in the QSR industry. The client requested a comprehensive Power BI dashboard to monitor financial KPIs, compare actual vs. budgeted revenue, and identify optimization opportunities.

### Objective  
To deliver an interactive dashboard capable of showing 5-year trends in Net Revenue, Gross Profit, EBITDA, PAT, and cost distribution — segmented by time, region, product category, and cluster head.

---

## 📊 Data  

### Data Source  
The data includes multiple Excel files (actuals + budget) with more than **480,000 rows** of transactional, financial, and SKU-level data.

### Data Description  
- Financial Metrics: Revenue, Profit, Cost, Discounts, Budget  
- Dimensions: Category, Channel, Time, Region, SKU, Cluster Head

---

## 🧠 Methodology  

### Approach  
- Data Cleaning (null handling, column renaming, format standardization)  
- Data Merging (actual + budget in a unified source)  
- ETL using Power Query  
- Data Modeling with Star Schema  
- Advanced DAX for dynamic measures  
- Visualization with advanced charts and conditional formatting

### Tools and Technologies  
- **Power BI**: Visualization, DAX, Modeling  
- **Microsoft Excel**: Data prep, merging, schema design  
- **Star Schema**: Fact-Dimension modeling  
- **DAX Measures**: YoY %, GP Margin, Cumulative %, Ranking

---

## 📈 Analysis and Findings  

### Financial Analysis  
- Tracked 5-year trend for Net Revenue, GP, EBITDA, and PAT  
- Revealed a 17% YoY gap in budget accuracy in 2022  
- Identified EBITDA fluctuations caused by poor cost allocation in certain regions

### SKU & Category Performance  
- Pareto analysis showed top 20% SKUs drive ~80% revenue  
- Mekko chart revealed category-level imbalance in SKU distribution vs. revenue  
- Bubble chart highlighted high-volume but low-margin product clusters

### Cluster & Location Insights  
- Cluster head performance visualized with Net Revenue vs GP%  
- Budgeting matrix flagged underperforming regions vs targets  
- Top cluster head (Anas) had 15% above-target GP% but low total revenue

---

## ✅ Recommendations  

- 🔍 Focus promotions on top-performing SKUs and high-margin categories  
- 🧮 Rationalize low-impact SKUs identified via Pareto + bubble analysis  
- 📍 Realign regional budgets where actual vs. budget deviation exceeds 10%  
- 📊 Leverage dashboards for monthly reviews of Cluster Head KPIs

---

## 📎 Ad Hoc Requests  

- 📌 Variance analysis across categories and clusters  
- 📌 Identify SKUs contributing less than 2% to revenue but over 5% to SKU count  
- 📌 Track MAT (Moving Annual Total) sales for last 3–6 months  
- 📌 Highlight loss-making products using color-coded conditional formatting  
- 📌 Rank top regions and clusters by EBITDA margin and cost efficiency

---

## 🧾 Conclusion  
This Power BI project empowers Crunchy Corner's executive and operations teams with real-time, interactive insights across 480K+ data points. It enables strategic planning, budget monitoring, and SKU-level optimization — with potential to drive **30–40% improvement in decision-making efficiency** and **15–25% impact on revenue optimization**.

---




