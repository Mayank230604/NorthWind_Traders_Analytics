# 📊 NorthWind Traders Analytics

> An end-to-end Data Analytics project on the Northwind Traders dataset — uncovering sales trends, customer segments, and shipping performance through SQL, Excel, and Power BI.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🚀 Project Overview

Northwind Traders is a fictional wholesale company. This project performs a full analytics pipeline — from raw SQL extraction to an interactive Power BI dashboard — to answer key business questions around **revenue, customer behaviour, product performance, and logistics**.

### Key Questions Answered
- Which products and categories drive the most revenue?
- Who are the highest-value customers, and where are they located?
- How does sales performance vary across time periods?
- Which shipping providers are causing delays, and at what cost?

---

## 🧰 Tech Stack

| Tool | Purpose |
|---|---|
| **SQL (PostgreSQL)** | Data extraction & querying |
| **Excel** | EDA, data cleaning & pivot analysis |
| **Power BI + DAX** | Data modeling, KPIs & dashboard |

---

## 📂 Dataset

The Northwind dataset includes 6 core tables:

`Customers` · `Orders` · `Order Details` · `Products` · `Employees` · `Shippers`

---

## 🔄 Workflow

```
SQL Extraction → Excel EDA & Cleaning → Power BI Modeling → DAX KPIs → Dashboard
```

1. **SQL** — Queried and joined tables to extract relevant business data
2. **Excel** — Exploratory analysis, pivot tables, and data validation (`EDA.xlsx`)
3. **Power BI** — Built star-schema data model and interactive visuals (`Northwind_Traders.pbix`)
4. **DAX** — Created calculated measures for revenue, growth rate, and customer ranking
5. **Reporting** — Exported findings to PDF and PowerPoint (`MECE.docx`, `.pptx`, `.pdf`)

---

## 📊 Key Insights

- **Top 10 customers** account for ~40% of total revenue, indicating high concentration risk
- **Beverages and Dairy Products** are the highest-grossing categories by revenue
- **Q4 consistently outperforms** other quarters — suggesting seasonal demand spikes
- **Speedy Express** has the lowest average delivery time; **United Package** shows the most delays
- **USA and Germany** lead in order volume, making them the most valuable regional markets

> *(Refine these with your actual numbers from the dashboard for maximum impact)*

---

## 📸 Dashboard Preview

<table>
  <tr>
    <td><img src="Images/01_introduction.png" alt="Overview"/><br/><sub><b>Overview</b></sub></td>
    <td><img src="Images/03_customers.png" alt="Customers Analysis"/><br/><sub><b>Customers Analysis</b></sub></td>
  </tr>
  <tr>
    <td><img src="Images/04_employees.png" alt="Employee Analysis"/><br/><sub><b>Employee Analysis</b></sub></td>
    <td><img src="Images/05_products.png" alt="Product Analysis"/><br/><sub><b>Product Analysis</b></sub></td>
  </tr>
  <tr>
    <td><img src="Images/06_shippers.png" alt="Shipper Analysis"/><br/><sub><b>Shipper Analysis</b></sub></td>
    <td><img src="Images/07_suppliers.png" alt="Supplier Analysis"/><br/><sub><b>Supplier Analysis</b></sub></td>
  </tr>
</table>

---
## 📁 Repository Structure

```
NorthWind_Traders_Analytics/
│
├── EDA.xlsx                          # Exploratory Data Analysis in Excel
├── MECE.docx                         # Structured problem breakdown (MECE framework)
├── Northwind_Traders.pbix            # Power BI dashboard file
├── Northwind_Traders.pdf             # Exported dashboard / report (PDF)
├── NORTHWIND-TRADERS-REPORT.pptx     # Presentation slides
└── README.md
```

---

## ⚡ How to Use

```bash
git clone https://github.com/Mayank230604/NorthWind_Traders_Analytics.git
cd NorthWind_Traders_Analytics
```

- Open `Northwind_Traders.pbix` in **Power BI Desktop** to explore the dashboard
- Open `EDA.xlsx` in **Excel** to review exploratory analysis and pivot tables
- Open `NORTHWIND-TRADERS-REPORT.pptx` for a summary presentation of findings

---

## 💼 Business Value

This analysis enables a business to:
- Prioritize high-value customer relationships for retention strategies
- Optimize inventory by focusing on top-performing product categories
- Identify seasonal demand patterns to improve forecasting and procurement
- Reduce shipping costs by evaluating shipper performance against SLAs

---

## 🧠 Skills Demonstrated

`SQL Querying` · `Data Cleaning` · `Exploratory Data Analysis` · `Data Modeling` · `DAX` · `Power BI Dashboarding` · `Business Analysis` · `Storytelling with Data`

---

## 🙋‍♂️ About Me

**Mayank Adeva** — Aspiring Data Analyst

B.Sc. Computer Science, Ramanujan College, University of Delhi (2025)
Skilled in SQL · Python (pandas, numpy) · Power BI · Excel · Git

📫 Open to entry-level Data Analyst roles — feel free to connect!

[![GitHub](https://img.shields.io/badge/GitHub-Mayank230604-181717?style=flat&logo=github)](https://github.com/Mayank230604)
