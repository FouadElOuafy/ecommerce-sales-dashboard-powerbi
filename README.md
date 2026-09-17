# 📊 E-Commerce Sales Dashboard & Customer Segmentation (Power BI)

Power BI dashboard analyzing e-commerce sales performance and customer segmentation (RFM analysis) using the Brazilian Olist public dataset (100k+ real orders, 2016-2018).

## 🎯 Project Overview

This project analyzes an e-commerce marketplace's sales data to answer key business questions:
- How has revenue evolved over time?
- Which product categories and regions drive the most revenue?
- How can customers be segmented based on purchasing behavior (RFM: Recency, Frequency, Monetary)?

## 🗂️ Dataset

[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — 100,000+ real orders from 2016 to 2018, including customer, product, payment, and review information.

## 🛠️ Tools & Skills

- **Power BI Desktop** — data modeling, DAX measures, interactive visuals
- **Power Query** — data cleaning and transformation
- **DAX** — custom measures and calculated columns for RFM segmentation
- **Data modeling** — star schema with 9 related tables

## 📈 Page 1 — Sales Overview

![Sales Overview](screenshots/page1_sales_overview.png)

- **Total Revenue**: 15.84M
- **Total Orders**: 99K
- **Average Order Value**: 159.33
- Revenue trend by quarter (2016-2018)
- Top 10 product categories by revenue
- Top 10 states by revenue (São Paulo leads with the highest share)

## 👥 Page 2 — Customer Segmentation (RFM Analysis)

![Customer Segmentation](screenshots/page2_customer_segmentation.png)

Customers were segmented into 6 groups based on Recency, Frequency, and Monetary value:
- **Champions** (0.7%) — highest average spend (~500+ per customer)
- **Clients Fidèles** (6%) — repeat buyers
- **Clients Satisfaits** (25.6%)
- **À Risque** (21.2%) — haven't purchased recently despite past spend
- **Clients Perdus** (19.3%)
- **Nouveaux Clients** (27.2%) — largest segment, recent first-time buyers

### 💡 Key Insight
Champions spend nearly **5x more on average** than new customers, despite representing less than 1% of the customer base — highlighting the value of retention strategies for high-value segments.

## 📥 Download the Dashboard

The `.pbix` file is hosted on Google Drive (file size exceeds GitHub's direct upload limit):

(https://drive.google.com/file/d/1XdAatWbVzXlepjoO3HzJB1KUWfkOoohH/view?usp=drive_link)

## 🚀 How to Use

1. Download the `.pbix` file from the link above
2. Open it with [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free)
3. Explore the interactive visuals and filters

---

*Built as a portfolio project to demonstrate data modeling, DAX, and business analytics skills in Power BI.*
