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

**Finance Page Overview:** This page is designed to enhance financial planning, optimize budgeting processes, and implement effective cost control measures. Key insights provided include:

- **Profit and Loss Statements:** A comprehensive view of financial performance.
- **Top and Bottom Products by Net Sales:** Identify the most and least profitable products.
- **Top and Bottom Customers by Net Sales:** Highlight key customer segments driving revenue and those requiring strategic attention.
  
By focusing on these metrics, the Finance Page ensures stakeholders can make informed financial decisions to drive business growth.

![Finance view](https://github.com/user-attachments/assets/403fba21-a6fb-4e8b-8e49-9ef7e37b5c71)

**Sales Page Overview:** The Sales Page is designed to drive revenue growth and expand market share by providing actionable insights. Key features include:

- **Customer Performance by Net Sales:** Analyze customer contributions to overall sales.
- **Gross Margin and Gross Margin %:** Evaluate profitability and efficiency across products or services.
- **Additional Sales Matrix:** Dive deeper into trends and patterns to uncover opportunities for growth.
  
This page empowers decision-makers with the insights needed to refine strategies, enhance customer engagement, and maximize profitability.

![Sales view](https://github.com/user-attachments/assets/43676863-a9e7-4233-b010-30709b1c11be)

**Marketing Page Overview:** The Marketing Page focuses on enhancing brand visibility and fostering customer engagement through data-driven insights. Key features include:

- **Segment Performance by Gross Margin %:** Assess the profitability of different market segments.
- **Segment Performance by Net Profit %:** Evaluate the net profitability across customer or product categories.
  
This page equips stakeholders with the tools to identify high-performing segments and boost overall marketing effectiveness.

![Marketing view](https://github.com/user-attachments/assets/4084473a-822b-4cb1-8ab1-87739d9a1db8)

**Supply Chain Page Overview:** The Supply Chain Page is designed to optimize inventory management and strengthen supplier relationships to achieve significant cost savings. Key insights include:

- **Forecast Accuracy:** Measure the precision of demand forecasting to reduce overstock and stockouts.
- **Net Error:** Analyze discrepancies between forecasted and actual demand.
- **Additional Supply Chain Metrics:** Identify opportunities to streamline operations and improve efficiency.
  
This page empowers decision-makers with the data needed to enhance supply chain performance, minimize waste, and maximize cost-effectiveness.

![Supply chain view](https://github.com/user-attachments/assets/8ee6e984-57c6-4dc9-9a51-c15dabcd9f70)

**Executive Page Overview:** The Executive Page offers a comprehensive performance overview tailored for top management, enabling quick and informed decision-making. Key highlights include:

- **Net Sales:** A snapshot of overall revenue performance.
- **Gross Margin % and Net Profit %:** Key profitability metrics to assess financial health.
- **Revenue Contribution by Channel:** Analyze performance across Retail, Direct Sales, and Distributors.
- **Top 5 Customers and Products:** Identify key revenue drivers.
- **Sub-Region Performance:** Evaluate geographical performance for targeted strategies.

This page consolidates critical metrics into a high-level dashboard, ensuring executives stay informed and aligned with organizational goals.

![Executive view](https://github.com/user-attachments/assets/c82a4014-b39f-4345-8dde-1243d88618a5)

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
