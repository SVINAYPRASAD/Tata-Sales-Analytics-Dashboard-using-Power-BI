# 📊 Tata Sales Analytics Dashboard

> An end-to-end sales analytics project built in **Power BI**, analysing **488,624 transactions** across **37 countries** (January – December 2011). The dashboard delivers actionable business insights on revenue performance, top products, regional distribution, and customer behaviour — all through an interactive and dynamic interface.

---

## 📸 Dashboard Preview

[Quantity and Revenue by Country](Tata%20Sales%20Analytics%20Dashboard/sales_analysis/Quantity_and_Revenue_by_Country.png)

[Quantity by Country (Map)](Tata%20Sales%20Analytics%20Dashboard/sales_analysis/Quantity_by_Country.png)

[Revenue by Customer ID](Tata%20Sales%20Analytics%20Dashboard/sales_analysis/Revenue_by_Customer_ID.png)

[Revenue by Month](Tata%20Sales%20Analytics%20Dashboard/sales_analysis/Revenue_by_Month.png)

---

## 🎯 Project Objective

Retail businesses need clear visibility into what's selling, where, and to whom. This project analyses Tata's 2011 retail sales data to answer:

- Which countries generate the most revenue and quantity sold?
- Who are the highest-value customers?
- How does revenue trend across the year?
- Where are the biggest international sales opportunities?

---

## 🗂️ Dataset Overview

- **Domain:** Retail / E-Commerce
- **Period Covered:** January 2011 – December 2011
- **Total Records:** 488,624 transactions
- **Total Revenue:** £9,842,938
- **Total Units Sold:** 5,229,137
- **Unique Customers:** 4,219
- **Unique Products:** 3,914
- **Countries Covered:** 37

| Column | Description |
|---|---|
| `InvoiceNo` | Unique invoice/order identifier |
| `StockCode` | Unique product code |
| `Description` | Product name |
| `Quantity` | Number of units sold per transaction |
| `InvoiceDate` | Date and time of the transaction |
| `UnitPrice` | Price per unit (£) |
| `CustomerID` | Unique customer identifier |
| `Country` | Country where the order was placed |
| `Revenue` | Total revenue for the transaction (Quantity × UnitPrice) |

---

## 💡 Key Insights

### 📦 1. Product Category Performance
Sales performance showed noticeable variation across different product categories — certain categories contributed significantly more to overall revenue, helping prioritise inventory and marketing focus.

### 👥 2. Customer Purchasing Behaviour
Customer analysis revealed clear patterns in buying trends, identifying **frequently purchased products** and **high-performing sales segments** to support targeted customer engagement strategies.

### 📅 3. Revenue Trend Analysis
Revenue trend analysis highlighted periods of increased sales activity — most notably a strong **Q4 surge peaking in November at £1.51M** — enabling better business planning and resource allocation.

### 📊 4. KPI Tracking
Key business metrics including **total sales (£9.84M)**, **revenue growth**, and **category-wise performance** were tracked through dedicated KPI cards for quick executive-level visibility.

### 🎛️ 5. Interactive Filters & Slicers
Interactive slicers allow users to dynamically explore sales data across **country, product, customer, and date dimensions** — making the dashboard flexible for multiple use cases.

### 📈 6. Data Visualisation
Complex datasets were simplified into meaningful insights through **bar charts, map visuals, line charts, and KPI cards** — making trends immediately visible without deep data expertise.

### 🗺️ 7. Country-wise Sales Distribution

| Country | Quantity | Revenue |
|---|---|---|
| Netherlands | 194K | £277K |
| EIRE (Ireland) | 141K | £273K |
| Germany | 112K | £214K |
| France | 107K | £200K |
| Australia | 83K | £137K |
| Spain | 27K | £60K |
| Switzerland | 30K | £56K |
| Belgium | 21K | £39K |
| Sweden | 32K | £35K |
| Norway | 16K | £32K |

> **Netherlands and Ireland lead international markets** by both quantity and revenue. Europe dominates with strong sales clusters visible on the map visual.

### 👤 8. Top Customers by Revenue

| Customer ID | Revenue |
|---|---|
| 14646 | £272K |
| 18102 | £252K |
| 17450 | £193K |
| 16446 | £168K |
| 14911 | £138K |
| 12415 | £125K |
| 14156 | £117K |
| 17511 | £84K |
| 12346 | £77K |
| 16029 | £68K |

> The **top 10 customers contribute a significant share of total revenue**, with Customer 14646 alone generating £272K. Retaining these high-value customers is critical to revenue stability.

### 🚀 9. Growth Opportunities
Sales distribution analysis provided better visibility into **underperforming regions and customer segments** — identifying clear opportunities for sales strategy improvement and market expansion.

### 🤝 10. Data-Driven Decision Making
This dashboard demonstrates the power of business intelligence tools in transforming **488,624 raw transactions** into structured, actionable insights that support smarter organisational decisions.

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Application |
|---|---|
| **Power BI Desktop** | Dashboard creation, data modelling, and visualisation |
| **Power Query** | Data cleaning, transformation, and shaping |
| **DAX (Data Analysis Expressions)** | Custom measures — total revenue, quantity, customer ranking |
| **Map Visual** | Geographic distribution of sales quantity by country |
| **Bar Charts** | Country-wise and customer-wise revenue comparison |
| **Line Chart** | Monthly revenue trend analysis |
| **Interactive Slicers** | Dynamic filtering by country, product, and date |

---

## 📂 Project Structure

```
Tata-Sales-Analytics-Dashboard/
│
├── sales_analysis/                              # Folder containing sales analysis files
├── Data Visualisation-Empowering Business.pdf   # Reference PDF document
├── insights.txt                                 # Business insights summary
├── Readme.md                                    # Project documentation
├── Tata Sales.xlsx                              # Raw dataset (488,624 records)
└── Tata_Sales_Analytics_Dashboard.pbix          # Power BI dashboard file
```

---

## 🚀 How to Open & Explore

1. Download `Tata_Sales_Analytics_Dashboard.pbix` and open in **Power BI Desktop** (free download from Microsoft)
2. Use the **slicers** on the dashboard to filter by Country, Product, or Date
3. Hover over visuals for **tooltips** with detailed breakdowns
4. The raw dataset (`Tata Sales.xlsx`) can be explored separately in Excel or Python
5. Refer to `insights.txt` for a summary of key business findings
6. The `Data Visualisation-Empowering Business.pdf` contains supporting reference material

---

## 🔮 Future Scope

- 🔗 Connect to a **live data source** for real-time sales tracking
- 📈 Add **revenue forecasting** using Power BI's built-in analytics pane
- 🤖 Build a **customer churn prediction model** using Python
- 📊 Publish to **Power BI Service** for web-based sharing and collaboration
- 🌍 Add deeper **international market analysis** beyond the UK

---

## 👤 About

This project was built as part of a data analytics portfolio to demonstrate skills in **data cleaning, data modelling, DAX, dashboard design, and business insight generation** using real-world retail sales data.


---

## 📄 License

Open for educational and portfolio use.
