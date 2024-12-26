# AtliQ Hardware Business Insights 360:
## Table of Contents:

**1.** [Project Overview](https://github.com/Nandankumars/Power-Bi-AtliQ-Hardware-Business-Insights-360/blob/main/README.md#project-overview) 

**2.** [Datasets](https://github.com/Nandankumars/Power-Bi-AtliQ-Hardware-Business-Insights-360/blob/main/README.md#datasets)

**3.** Power BI Dashboard Overview

**4.** Power BI Techniques Learned

**5.** Tools Used

**6.** Business Terms Learned

## Project Overview:

AltiQ Hardware is a fast-growing global company, specializes in selling computers and accessories through three primary channels: retailers, direct sales and distributors. Despite its rapid growth, the company encountered unexpected losses after opening a new store in America. These challenges were initially identified through surveys, intuition, and basic Excel analysis.

With competitors leveraging advanced analytics teams, AltiQ Hardware recognized the need to build robust analytics capabilities to remain competitive in the industry.

To gain an edge and embrace data-driven decision-making, AltiQ Hardware initiated the implementation of Power BI for analytics. The goal of this project was to equip stakeholders with actionable insights across finance, sales, marketing, supply chain functions, enabling informed decision-making at every level.

I contributed to this transformative project by applying skills gained from the Codebasics Power BI Course, ensuring a structured approach to developing impactful dashboards and reports.

Live Dashboard link - [Click Here](https://app.powerbi.com/view?r=eyJrIjoiOWM2YWQyMjYtYzcxMS00ZDFlLThkOTgtZTk0Njc2MzQyNDYxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Datasets:
Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

**gdb041:**

- **dim_customer**
- **dim_market**
- **dim_product**
- **fact_forecast_monthly** - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
- **fact_sales_monthly** - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

**gdb056:**

- **freight_cost**
- **gross_price**
- **manufacturing_cost**
- **Pre_invoice_dedutions**
- **Post_invoice_deductions**
  
### The Importance of Data Modeling in Analytics

For this project, data was imported from MySQL into Power BI, where it was cleaned, transformed, and structured into a robust data model. 
But why is data modeling so critical for analysis?

If we break down the work of a data analyst, it typically involves four key steps:

✅ Data Extraction → ✅ Data Cleaning → ✅ Data Modeling → ✅ Data Analysis

The third step—Data Modeling—is indispensable if you want to reach the final step, Data Analysis. It serves as the backbone of any analytical report. A well-designed data model not only ensures accurate and efficient analysis but also enhances report performance and interactivity. Poor modeling, on the other hand, can lead to sluggish reports and unreliable insights.

In this project, we adopted the Snowflake schema for data modeling, ensuring a scalable and optimized foundation for building meaningful visualizations and reports.
![Data modelling](https://github.com/user-attachments/assets/b653affc-8d61-4752-aecc-9c0d30f8beab)

## Power BI Dashboard Overview:
The dashboard comprises six pages

**Home Page:** A landing page with buttons to navigate to different pages.
![Home](https://github.com/user-attachments/assets/f911b8b6-b381-4e34-bd45-47413d07c0f8)

## Technologies and Techniques Used in Business Intelligence Dashboard:
This repository leverages a suite of technologies and advanced techniques to build powerful and interactive Business Intelligence dashboards.

## Technologies Used:

### Power BI:

- Interactive data visualization and reporting platform.

### Excel:

- For initial data preprocessing and exploratory analysis.
  
### SQL:

- Data extraction, querying, and manipulation from relational databases.
  
### DAX (Data Analysis Expressions):

- Advanced calculations and custom measures in Power BI.

### Power Query:

- ETL (Extract, Transform, Load) tool for data transformation and shaping.

### Database= MySQL:

- Back-end database for data storage and querying.

## Power BI Techniques Learned:

**1. Data Importing and Integration:**
- Connecting to diverse data sources (Excel, SQL databases, APIs, etc.).
- Merging and appending data from multiple sources to create unified datasets.
  
**2. Data Transformation with Power Query:**
- Cleaning and preparing raw data for analysis.
- Addressing missing or inconsistent data using Power Query Editor.
- Applying advanced transformations to ensure data readiness.
 
**3. Data Modeling:**
- Establishing relationships between tables to enable seamless analysis.
- Designing star and snowflake schemas for optimized performance.
- Creating calculated columns and tables for enriched insights.
  
**4. DAX (Data Analysis Expressions):**
- Writing measures for advanced analytics and custom KPIs.
- Utilizing DAX functions like CALCULATE, FILTER, and SUMX.
- Dynamic calculations for robust and flexible reporting.

**5. Visualization Techniques:**
- Designing interactive and user-friendly dashboards.
- Employing various visuals such as bar charts, slicers, maps, and tables.
- Customizing visuals for impactful storytelling and data-driven insights.

**6. Interactivity and Filtering:**
- Adding slicers, drill-throughs, and bookmarks for navigation and segmentation.
- Syncing filters across pages for consistent interactivity.

**7. Performance Optimization:**
- Optimizing data models to reduce report load time.
- Implementing aggregations and summarizations for efficient reporting.

**8. Publishing and Sharing:**
- Publishing reports to Power BI Service for accessibility.
- Scheduling automatic data refreshes to ensure up-to-date insights.
- Sharing dashboards securely with stakeholders.

## Key Financial and Business Terms:

### Financial Metrics:
- **Gross Price:** Total price of goods or services before any deductions.
- **Pre-Invoice Deductions:** Discounts or allowances applied before invoice generation.
- **Post-Invoice Deductions:** Adjustments or deductions made after the invoice is issued.
- **Net Invoice Sale:** Revenue received after all deductions.
- **Gross Margin:** Difference between revenue and COGS, expressed as a percentage.
- **Net Sales:** Revenue after subtracting returns, allowances, and discounts.
- **Net Profit:** Profit after deducting all expenses, taxes, and deductions.

### Operational Terms:
- **COGS (Cost of Goods Sold):** Direct costs associated with producing goods.
- **YTD (Year to Date):** Period from the start of the current year to the present date.
- **YTG (Year to Go):** Remaining period in the current year.

### Distribution and Retail Terms:
- **Direct:** Sales made directly to end consumers without intermediaries.
- **Retailer:** A business that sells goods to consumers, typically in smaller quantities.
- **Distributors:** Intermediaries who purchase goods in bulk and supply to retailers.
- **Consumer:** The end user purchasing goods or services for personal use.
