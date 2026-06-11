# FreshMart Sales Analytics Dashboard — Power BI

An end-to-end retail sales analytics project built in Power BI using a simulated 6-month dataset of a fictional Indian retail chain called FreshMart.

---

## Project Overview

FreshMart operates across 4 cities in Maharashtra — Mumbai, Pune, Nagpur, and Aurangabad. This dashboard analyzes 177 transactions from January to June 2024 to uncover sales trends, store performance, category insights, discount effectiveness, and payment preferences.

---

## Dashboard Pages

### Page 1 — Sales Performance Overview
- Total Revenue, Total Transactions, and Avg Revenue per Transaction (KPI cards)
- Monthly revenue trend (Jan–Jun 2024)
- Revenue by store city
- Revenue by product category
- Revenue by customer age group
- Month slicer for interactive filtering

### Page 2 — Deep Dive Analysis
- Revenue by discount type (No Discount / 5% / 10%)
- Revenue by payment mode (Card / UPI / Cash)
- Payment mode preference by city (stacked bar)
- Product category slicer for interactive filtering

---

## Key Findings

| Finding | Insight |
|---|---|
| Top store | Mumbai (₹24.6K) |
| Weakest store | Nagpur (₹16.4K) — needs strategic focus |
| Top category by revenue | Staples (₹32K) — despite Snacks leading in units sold |
| Underperforming category | Personal Care (₹11K) — below its potential |
| Revenue trend | Grew nearly 3× from Jan (₹7.4K) to May/Jun (₹20.7K) |
| Discount impact | Minimal — non-discounted items drive 68% of revenue |
| Payment modes | Evenly split — Card 35%, UPI 34%, Cash 31% |
| Top customer segment | Adults (68% of revenue) |

---

## Skills Applied

- **Power BI** — report building, slicers, two-page dashboard structure
- **DAX Calculated Columns** — `Revenue = Units_Sold * Unit_Price * (1 - Discount_% / 100)`
- **DAX Calculated Columns** — `Discount_Type` (No Discount / 5% Discount / 10% Discount)
- **DAX Measures** — `Avg Revenue per Transaction = DIVIDE([Total Revenue], [Total Transactions])`
- **Data Visualization** — bar charts, line chart, donut chart, stacked bar chart
- **Dashboard Design** — insight-driven titles, subtitles, data labels, consistent color theme

---

## Dataset

- Simulated dataset created for practice purposes
- 177 transactions | Jan–Jun 2024
- 4 store cities: Mumbai, Pune, Nagpur, Aurangabad
- 5 product categories: Staples, Dairy, Snacks, Beverages, Personal Care
- Fields: Transaction_ID, Date, Store_City, Store_ID, Product_Category, Product_Name, Units_Sold, Unit_Price, Discount_%, Customer_Age_Group, Payment_Mode

---

## Files

| File | Description |
|---|---|
| `freshmart_sales.csv` | Raw dataset |
| `FreshMart_Dashboard.pbix` | Power BI dashboard file |
| `screenshots/` | Dashboard screenshots |

---

## Screenshots

> Add your dashboard screenshots here after uploading

---

## Author

**Meher**  
B.Tech Student — P. R. Pote Patil College of Engineering & Management, Amravati 
