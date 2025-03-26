Power BI Sales Dashboard

1. Project Overview

This dashboard provides highly informative insights into a company's sales performance by analyzing customer data across multiple regions and periods of time. It provides a simple, interactive, and intuitive layout to aid stakeholders in tracking useful key performance indicators (KPIs), identifying trends, revealing context, and supporting informed decision-making.

2. Features

Interactive Visualizations: Interact with charts and graphs to drill down into specific data points. (Tool Tip, Slicers)

Data Filters: Data can be filtered by time periods, regions, or other key attributes. (Date and Feature Filters/Slicers)

Measures: Measures created using DAX to compute key performance indicators and other valuable features.

Performance Metrics: Displays truly insightful KPIs like Revenue, Revenue Contribution %, Profit Margin %, Profit Margin Contribution %, etc., adding crucial context while gauging performance.

Reports: Includes different report pages for alternate perspectives on the data.

3. Installation

To use this Power BI dashboard:

Download the Dashboard pbi project.pbix file and the db_dump.sql file from the repository.

Open Power BI Desktop.

Open the Dashboard pbi project.pbix file using Power BI Desktop.

Open MySQL Workbench CE, create a connection, and load the data using the Server > Data Import option.

Connect to the data source on Power BI using the Get Data > MySQL Database option and entering the required credentials or configurations.

4. Data Sources

Source 1: db_dump.sql (8.6 MB)

An SQL Server database with 5 tables:

sales_customer: Customer information like Customer ID, Name, and Type

sales_date: Date, month, year

sales_market: Information on different markets where business is conducted, including Market Name, Zone, and Code

sales_products: Product information like Product Name and Code

sales_transactions: The Facts table where information about every transaction lies, including details about Product, Customer, Market, Date, Currency, Sales Amount, Quantity, etc.

5. How to Use

Navigating the Dashboard:

The dashboard includes various pages. Use the tabs at the bottom to switch between pages.

Interactive visuals allow you to drill down into specific data by clicking on the charts, using slicers, or hovering over to reveal the tooltip.

