1. Project Overview
  This dashboard provides highly imformative insights into a company's sales performance by analyzing customer data across multiple regions and periods of time.
  It provides a simple, interactive and intutive layout to aid stakeholders track useful key performance indicators (KPIs), identify trends, reveal context and support informed decision making.
2. Features
   - Interactive Visualisations : Interact with charts and graphs to drill down into specific data points. (Tool Tip, Slicers)
   - Data Filters : Data can be filtered by time periods, regions, or other key attributes. (Date and Feature Filters/Slicers)
   - Measures : Measures created using DAX to compute key performance indicators and other valuable features.
   - Performance Metrics : Displays truly insightful KPIs like Revenue, Revenue Contribution %, Profit Margin %, Profit Margin Contribution %, etc. adding crucial context while guaging performance.
   - Reports : Includes different report pages for alternate perspectives on the data.
3. Installation
  To use this Power BI dashboard :
    - Download the "Dashboard pbi project.pbix" file and the "db_dump.sql" file from the repository.
    - Open Power BI Desktop.
    - Open the "Dashboard pbi project.pbix" file using Power BI Desktop.
    - Open MySQL Workbench CE, create a connection and load the data using the Server > Data Import option.
    - Connect to the data source on Power BI using the Get Data > MySQL Database option and entering the required credentials or configurations.
4. Data Sources
  Source 1: "db_dump.sql" (8.6 MB)
    - An SQL Server database with 5 Tables i) sales customer - Customer information like Customer ID, Name and Type
                                           ii) sales date - date, month, year
                                           iii) sales market - Information on different markets where business is done like Market Name, Zone and Code
                                           iv) sales products - Product information like product name and code
                                           v) sales transactions - The Facts table where information about every transaction lies. Information regarding Product, Customer, Market, Date, Currency, Sales amount, Quantity, etc.
5. How to Use
  Navigating the Dashboard :
    - The dashboard includes various pages. Use the tabs at the bottom to switch between pages.
    - Interactive visuals allow you to drill down into specific data by clicking on the charts, using slicers or hovering over to reveal the tooltip.
