# Business Insights 360

## Project Overview

AtliQ Hardware is rapidly expanding and has decided to implement data analytics using Power BI to stay ahead of competitors and make data-driven decisions. This project addresses stakeholder questions across finance, sales, marketing, and supply chain. The project followed the Codebasics Power BI Course.

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYzEzODcyMGEtZDkwNi00YTYzLWE5ZTEtMmFiODdjYzQ1OTc4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech Stack

- SQL
- Power BI Desktop
- Excel
- DAX
- DAX Studio
- Project Charter File

## Power BI Techniques Learned

- Project scoping questions
- Calculated columns and measures using DAX
- Data modeling
- Bookmarks for visual switching
- Page navigation with buttons
- Zero division error prevention
- Creating date tables with M language
- Dynamic titles based on filters
- KPI indicators
- Conditional formatting
- Data validation
- Power BI services: publishing, personal gateway setup, app creation, collaboration, workspace, and access permissions

## Key Business Terms

- Gross Price
- Pre-Invoice Deductions
- Post-Invoice Deductions
- Net Invoice Sale
- Gross Margin
- Net Sales
- Net Profit
- COGS (Cost of Goods Sold)
- YTD (Year to Date)
- YTG (Year to Go)
- Direct, Retailer, Distributors
- Consumer

## Company Background

AtliQ Hardware sells computers and accessories globally through retailers, direct sales, and distributors. Recently, the company faced losses due to non-data-driven decisions and competitors' strong analytics teams. To survive and thrive, AtliQ Hardware is building an analytics team for future insights and decisions.

## Initial Project Questions

- Project objectives and success metrics
- Timeline and preview expectations
- Stakeholder hopes, fears, and usage
- Design and view inputs
- Resources and data needs
- Potential project risks

## Dataset Understanding

### Dimension Tables

- **dim_customer:** 27 markets, 75 customers, 2 platforms (Brick & Mortar, E-commerce), 3 channels (Retailer, Direct, Distributors)
- **dim_market:** 27 markets, 7 sub-zones, 4 regions (APAC, EU, NAN, LATAM)
- **dim_product:** Divisions (P & A, PC, N & S), 14 categories, various variants

### Fact Tables

- **fact_forecast_monthly:** Forecasted customer needs, denormalized, start date of month
- **fact_sales_monthly:** Similar to forecast table, with sold quantity instead

### Other Tables

- **freight_cost:** Travel and other costs by market and fiscal year
- **gross_price:** Gross prices by product code
- **manufacturing_cost:** Manufacturing costs by product code and year
- **pre_invoice_deductions:** Pre-invoice deductions by customer and year
- **post_invoice_deductions:** Post-invoice and other deductions

## Data Import and Modeling

- Import datasets from MySQL to Power BI using database credentials
- Data modeling is crucial for performance; followed snowflake modeling method

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view

![1 Home_BI](https://github.com/SandeepChinta4/Business-Insights-360/assets/137393739/ebbe2374-ebaa-48ea-85cb-171969c12e58)

## Finance View

![2 Finance View_BI](https://github.com/SandeepChinta4/Business-Insights-360/assets/137393739/0db3ea3a-ecd1-49ff-a75e-78e2087f133b)

## Sales View

![3 Sales View_BI](https://github.com/SandeepChinta4/Business-Insights-360/assets/137393739/c4c5d901-d86a-40dd-8608-9d9630fce6b0)

## Marketing View

![4 Marketing view](https://github.com/SandeepChinta4/Business-Insights-360/assets/137393739/97fc55ea-2308-423c-b448-1762d7d4094a)

## Supply chain View

![5 Supply Chain View](https://github.com/SandeepChinta4/Business-Insights-360/assets/137393739/e4a610c9-ba45-48dc-9f15-2d045afe0f21)

## Executive View

![6 Executive View](https://github.com/SandeepChinta4/Business-Insights-360/assets/137393739/92590468-0a07-4659-80e2-6d18fc26d12a)


## Project Outcome

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.
