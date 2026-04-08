# E-Commerce Sales Analytics

---

## Project Summary
This project demonstrates a complete data analytics workflow using an e-commerce sales dataset. It covers data loading, querying, analysis, and visualization using multiple tools.

The goal is to extract meaningful business insights and present them through structured queries and interactive dashboards.

---

## Workflow
- Import dataset into MySQL
- Perform data cleaning and analysis using SQL
- Build summary reports in Excel
- Create interactive dashboards in Tableau

---

## Dataset Details
- File: `ecommerce_dataset.csv`
- Total Records: 200

### Columns
- order_id
- customer_id
- product
- category
- quantity
- price
- order_date
- month
- region
- revenue
- recency

---

## Tools and Technologies
- MySQL for data storage and querying
- Excel for pivot tables and basic visual analysis
- Tableau for dashboard creation
- GitHub for project hosting

---

## SQL Analysis
All queries are written in a simple and readable format.

File: `queries.sql`

### Sample Queries
- Total number of orders
- Count of unique customers
- Top products based on revenue
- Monthly sales performance

---

## Dashboard and Analysis

### Tableau Dashboard
File: `Tableau_Dashboard.twbx`

Includes:
- Product performance analysis
- Customer contribution insights
- Regional revenue distribution
- Monthly sales trends
- Key performance indicators such as revenue, orders, and average order value

---

### Excel Analysis
File: `Excel_Analysis.xlsx`

Includes:
- Monthly revenue trends
- Category-wise performance
- Customer segmentation
- Top-selling products
- Revenue per customer
- Regional comparisons

---

## Project Files
- `insert_sales.sql` – SQL script to load dataset
- `queries.sql` – SQL queries for analysis
- `ecommerce_dataset.csv` – raw dataset
- `Excel_Analysis.xlsx` – Excel-based analysis
- `Ecommerce_Sales_Analytics_Report.pdf` – project report
- Tableau dashboard files and images

---

## Key Findings
- Certain product categories generate significantly higher revenue than others
- Specific regions contribute more to overall sales
- Sales show seasonal patterns with noticeable monthly variation
- A segment of customers contributes disproportionately to total revenue
- Average order value indicates consistent customer spending behavior

---

## Setup Instructions
- Import the dataset using `insert_sales.sql` into MySQL
- Execute queries from `queries.sql`
- Open the Excel file for spreadsheet-based insights
- Launch the Tableau workbook to explore the dashboard

---

## Conclusion
This project highlights the integration of SQL, Excel, and Tableau to transform raw data into actionable insights. It demonstrates practical skills in data analysis, visualization, and reporting.
