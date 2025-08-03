![Dashboard Image](dashboard.png)

## Online Retail Sales Performance Dashboard

This project demonstrates my skills in data analysis, business intelligence, and data visualization using Power BI. The goal was to transform and analyze a dataset of online retail transactions to create a comprehensive dashboard that provides insights into sales performance.

### Project Overview

This dashboard was built using the **Online Retail** dataset, a publicly available dataset from the UCI Machine Learning Repository. It covers transactional data from a UK-based online retailer. The project involved the following key steps:

- **Data Acquisition:** Sourcing the raw data from the provided CSV file.
- **Data Transformation:** Cleaning and shaping the data in Power Query Editor.
- **Data Modeling:** Creating a logical data model in Power BI.
- **DAX Calculations:** Writing custom DAX measures to calculate key performance indicators (KPIs).
- **Data Visualization:** Designing an interactive dashboard to present the findings.

**Dataset Link:** [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

### Dashboard Highlights

The final dashboard provides a high-level overview of the company's sales performance. Key metrics and visualizations include:

- **Total Customers:** The total number of unique customers served.
- **Total Sales:** The total number of transactions.
- **Total Amount of Sales:** The gross revenue generated.
- **Returns:** The total value of returned items.
- **Net Revenue:** The total sales minus the value of returns.
- **Geographic Analysis:** A map showing the top 5 performing countries.
- **Sales Trend Analysis:** A line chart visualizing sales performance over time, including a forecast.
- **Sales by Year:** A doughnut chart showing the distribution of sales across different years.

---

### Technical Skills Demonstrated

This project allowed me to apply and develop a range of technical and analytical skills crucial for a Business Analyst:

- **Data Cleaning and Transformation:** I used Power Query Editor to handle data preparation tasks, including:
  - **Changing Data Types:** Ensuring columns like dates and numbers were in the correct format.
  - **Handling Missing Values:** Identifying and addressing null or empty entries.
  - **Creating Custom Columns:** Calculating new columns to derive valuable information, such as **Total Amount** (`Quantity` \* `UnitPrice`).
- **DAX (Data Analysis Expressions):** I wrote several DAX measures to create meaningful metrics, including:
  - **Total Number of Customers:** Using `DISTINCTCOUNT` to count unique customer IDs.
  - **Total Number of Sales:** Using `DISTINCTCOUNT` to count unique invoice numbers.
  - **Total Amount of Sales:** Using `SUM` to aggregate the newly created `Total Amount` column.
  - **Total Amount of Returns:** Using `CALCULATE` with a `FILTER` to sum only transactions where the **Total Amount** was negative.
- **Data Visualization & Storytelling:** I designed a clear and intuitive dashboard that effectively communicates key insights to stakeholders. This involved selecting appropriate chart types (e.g., line charts for trends, maps for geographic analysis, and KPI cards for key metrics) to tell a coherent data story.
- **Business Acumen:** I applied a business-oriented mindset to identify and calculate relevant KPIs (e.g., Net Revenue, Returns) that are critical for understanding and improving business performance.

---

### Future Enhancements

Potential future developments for this project include:

- Adding a time dimension table to enable more flexible time-based analysis.
- Including a customer segmentation analysis to identify high-value customers.
- Implementing drill-through pages to explore detailed transaction information.
