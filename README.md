# Power BI Sales Dashboard

## 1. Project Overview
This dashboard provides highly informative insights into a company's sales performance by analyzing customer data across multiple regions and periods of time.  
It provides a simple, interactive and intutive layout to aid stakeholders track useful key performance indicators (KPIs), identify trends, reveal context and support informed decision making.

## 2. Features
- **Interactive Visualizations**  
  Interact with charts and graphs to drill down into specific data points. (Tool Tip, Slicers)  

- **Data Filters**  
  Data can be filtered by time periods, regions, or other key attributes. (Date and Feature Filters/Slicers)  

- **Measures**  
  Measures created using DAX to compute key performance indicators and other valuable features.

- **Data Model**
  Designed and implemented a star schema including fact tables (sales_transactions) and dimension tables (sales_customers, sales_products, sales_date, sales_market, sales_product). This model ensures efficient querying and data relationships.

- **Performance Metrics**  
  Displays truly insightful KPIs like Revenue, Revenue Contribution %, Profit Margin %, Profit Margin Contribution %, etc. adding crucial context while guaging performance. 

- **Reports**  
  Includes different report pages for alternate perspectives on the data.

## 3. Installation
To use this Power BI dashboard:

1. Download the following files from the repository:
   - **Dashboard pbi project.pbix**
   - **db_dump.sql**
2. Open **Power BI Desktop**.
3. Load the dashboard:
   - Open the **"Dashboard pbi project.pbix"** file in Power BI Desktop.
4. Set up the database:
   - Open **MySQL Workbench CE**.
   - Create a connection and load the data using **Server > Data Import**.
5. Connect to the database in Power BI:
   - Use **Get Data > MySQL Database**.
   - Enter the required credentials and configurations.

## 4. Data Sources

### Source 1: `db_dump.sql` (8.6 MB)
An SQL database with 5 tables:

1. **sales_customer**  
   Customer information: Customer ID, Name, Type  

2. **sales_date**  
   Date information: Date, Month, Year  

3. **sales_market**  
   Market details: Market Name, Zone, Code  

4. **sales_products**  
   Product information: Product Name, Code  

5. **sales_transactions**  
   Transaction details: Product, Customer, Market, Date, Currency, Sales amount, Quantity  

## 5. How to Use

### Navigating the Dashboard:
- Use the tabs at the bottom to switch between report pages.
- Interactive visuals allow you to:
  - Drill down into specific data by clicking on charts.
  - Filter using slicers (e.g., Date, Region).
  - Hover over visuals to view detailed tooltips.
