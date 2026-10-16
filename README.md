# 📊 Customer Balance Financial Dashboard (Power BI)

> ⚠️ **Confidentiality Notice:** 
> *Due to strict data privacy and confidentiality agreements, the underlying datasets, data models, and `.pbix` files cannot be shared publicly. This repository serves as a visual and methodological case study to demonstrate my Power BI development and data modeling capabilities.*

## 📌 Project Overview
This project features an interactive financial dashboard designed to track and analyze **Customer Balances** over time. The dashboard provides stakeholders with a clear view of financial health, highlighting total balances, debit/credit movements, and year-over-year distribution to support strategic financial decision-making.

*(Dashboard UI is in Arabic, reflecting the local business requirements of the client).*

## ️ Tools & Technologies
- **Visualization:** Microsoft Power BI
- **Data Modeling:** Star Schema design, Relationship management
- **Calculations:** DAX (Data Analysis Expressions)
- **Data Preparation:** Power Query (ETL)

## 🔍 What I Did (Methodology)

### 1. Data Modeling & ETL
- Cleaned and transformed raw transactional data using **Power Query**.
- Designed a robust **Star Schema** data model, establishing proper one-to-many relationships between the Fact tables (Transactions/Balances) and Dimension tables (Customers, Dates, Accounts).

### 2. DAX Measures Development
- Created complex DAX measures to calculate dynamic financial metrics, including:
  - **Total Balance (الرصيد):** Aggregating net financial positions.
  - **Debit (مدين) & Credit (دائن):** Segregating transactional flows for accurate ledger tracking.
  - **Time Intelligence:** Implementing Year-to-Date (YTD) and period-over-period comparisons to track financial trends across the 2020–2026 timeline.

### 3. Dashboard Design & UX
- **Trend Analysis:** Implemented a clustered bar chart to visualize balance fluctuations and spikes over time, allowing users to identify seasonal trends or anomalies.
- **Distribution Analysis:** Added a Donut chart ("Balance by Year") to show the proportional contribution of each fiscal year to the total portfolio.
- **Detailed Drill-Down:** Built a comprehensive matrix/table displaying Account Codes, Names, Balances, Debits, and Credits, enabling finance teams to drill down into specific ledger details.
- **KPI Cards:** Highlighted the grand total (1.57M) at a glance for executive-level reporting.

## 💡 Key Business Insights Delivered
- Enabled the finance team to quickly identify high-value accounts and track their debit/credit behaviors.
- Provided a centralized, automated view of customer balances, replacing manual Excel tracking and reducing reporting time.
- Highlighted significant balance spikes in specific years (e.g., 2023 and 2024), prompting further financial auditing and strategy adjustments.

##  Contact
- **Email:** ibrahim.fadyy@gmail.com
- **LinkedIn:** linkedin.com/in/ibrahim-fady
