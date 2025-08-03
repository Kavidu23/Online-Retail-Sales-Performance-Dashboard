# 📊 Online Retail Sales Performance Dashboard

This project showcases my skills in data analysis, business intelligence, and data visualization using **Power BI**. The objective was to transform raw retail transaction data into an insightful dashboard to analyze sales performance and customer behavior.

![Dashboard](dashboard.png)

---

## 🗂️ Project Overview

Built using a publicly available dataset, this dashboard includes end-to-end business intelligence steps:

- 📥 **Data Acquisition:** Loaded raw sales data from CSV.
- 🧹 **Data Transformation:** Cleaned and shaped data in **Power Query Editor**.
- 🧠 **Data Modeling:** Created relationships and structured the model in Power BI.
- 🧾 **DAX Calculations:** Developed custom measures for KPIs.
- 📈 **Visualization:** Designed a responsive and dynamic dashboard.

**Dataset Source:**  
[Online Retail Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)

---

## 📌 Dashboard Insights

The final dashboard includes key metrics and visuals:

- 🧍‍♂️ **Total Customers:** Unique customers served.
- 🧾 **Total Sales:** Number of transactions (Invoice count).
- 💰 **Total Amount of Sales:** Total revenue generated.
- 🔁 **Returns:** Value of returned products (based on negative quantities).
- 🧮 **Net Revenue:** Sales revenue minus returns.
- 🌍 **Top Countries:** Geographic map of top-performing countries.
- 📊 **Sales Trend:** Line chart with quarterly breakdown and forecasting.
- 📆 **Year-wise Sales Distribution:** Donut chart breakdown by year.

---

## 🛠️ Technical Highlights

- 🧼 **Data Cleaning in Power Query:**

  - Removed nulls and non-numeric entries.
  - Converted data types (e.g., Quantity, UnitPrice, Dates).
  - Added new calculated columns like `Total Amount = Quantity * UnitPrice`.

- 🧮 **DAX Measures Created:**

  - `Total Customers = DISTINCTCOUNT(CustomerID)`
  - `Total Sales = DISTINCTCOUNT(InvoiceNo)`
  - `Total Amount of Sales = SUM(Total Amount)`
  - `Returns = CALCULATE(SUM(Total Amount), FILTER(...))`
  - `Net Revenue = [Sales] - [Returns]`

- 📈 **Forecasting:**
  - Enabled in the line chart for future sales trend estimation.

---

## 🚀 Skills Demonstrated

- Power BI Development
- Power Query Editor
- DAX (Data Analysis Expressions)
- Business Intelligence Strategy
- Data Visualization and Storytelling
- KPI and Metric Design
- Forecasting in Visuals
- Real-World Retail Use Case Analysis

---

## 🔮 Future Improvements

- Add date dimension table for advanced time intelligence.
- Perform RFM analysis to identify high-value customers.
- Include drill-through reports for invoice-level analysis.
- Add return rate percentage and regional profitability breakdowns.

---
