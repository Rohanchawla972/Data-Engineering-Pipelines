# Advanced Sales & Marketing Data Warehousing with Azure Data Factory

## Overview
This project focuses on designing and implementing a **Sales & Marketing Data Warehouse** for *Adventure Works Cycles*.  
It leverages:
- **Azure Data Factory (ADF)** for ETL workflows  
- **Azure Data Studio** for querying OLTP & OLAP databases  
- **Azure SQL Database** for structured storage  

The solution enables **business intelligence analytics** across sales and marketing, supporting **customer segmentation, discount impact analysis, demand forecasting, and trend analysis**.

---

## Objectives
- Build a centralized **sales & marketing data warehouse**.  
- Design and automate **ETL pipelines** using Azure Data Factory.  
- Transform normalized **OLTP databases → denormalized OLAP schema**.  
- Provide insights for **decision-making** in sales optimization, campaign performance, and forecasting.  

---

## Methodology
1. **ETL Pipelines**  
   - Data extracted from transactional sources.  
   - Cleaned, transformed, and loaded into the data warehouse.  

2. **Star-Schema Architecture**  
   - Fact tables: Sales, Marketing, Discounts.  
   - Dimension tables: Customers, Products, Time, Geography.  

3. **Analytics Layer**  
   - Customer segmentation (loyal vs. new buyers).  
   - Discount impact on sales uplift.  
   - Forecasting future demand trends.  

---

## Repository Structure
```plaintext
 SQL-Sales-Marketing-DataWarehouse
 └── 📂 ADF_ETL_Sales_Analytics
     ├── 📄 AdvancedSales&MarketingDataWarehousingwithAzureReport.pdf   # Full project report
     ├── 📄 README.md
```
## Key Deliverables
- **ETL Workflows**: Automated pipelines built in Azure Data Factory to extract, transform, and load sales and marketing data.  
- **Star-Schema OLAP Model**: Fact and dimension tables designed for efficient querying and reporting.  
- **Advanced Analytics**: Insights into customer segmentation, discount effectiveness, and demand forecasting.  
- **Business Intelligence Reports**: Data-driven dashboards and visualizations enabling informed decision-making.  
- **Comprehensive Project Report (PDF)**: Full documentation of methodology, data model, and findings.  




