# powerbi-global-superstore-

# Global Superstore Business Intelligence Dashboard | Power BI

## Project Overview

This project focuses on developing an interactive Business Intelligence (BI) dashboard using Microsoft Power BI to analyze the business performance of a global retail company called Global Superstore.

The dashboard provides insights into sales, profitability, customer segments, product categories, shipping performance, and regional performance. 
It helps users understand business trends and supports data-driven decision-making.

## Project Objectives

- Analyze overall sales and profit performance.
- Evaluate customer segments and customer contributions to revenue.
- Identify the best and worst-performing products and product categories.
- Analyze sales performance across different countries and regions.
- Evaluate shipping performance and operational trends.
- Identify business trends and significant changes in sales and profit.
- Present business insights through interactive visualizations.

## Tools and Technologies

- **Microsoft Power BI Desktop** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX (Data Analysis Expressions)** – Calculations and measures.
- **Power BI Data Model** – Organizing tables and establishing relationships.

## Dataset Description

The project uses the Global Superstore dataset, which contains business information related to:

- Orders and shipments
- Customers and market segments
- Products, categories, and subcategories
- Countries and geographical regions
- Sales, discounts, quantities, and profits

*Note: The dataset was provided as part of the university assignment.*

## Project Workflow

### 1. Data Cleaning and Transformation

- Imported the provided dataset into Power BI.
- Performed data cleaning and transformation using Power Query.
- Prepared the data for analysis by checking data formats and structures.
- Organized the data for further analysis.

### 2. Data Modeling

- Organized the datasets into a structured data model.
- Established relationships between relevant tables.
- Prepared the model to support analysis across different business dimensions.

### 3. DAX Calculations and Measures

Used DAX (Data Analysis Expressions) to perform business calculations and support performance analysis.

Examples of relevant DAX measures:

**Total Sales**
```dax
Total Sales = SUM(Orders[Sales])
```

**Total Profit**
```dax
Total Profit = SUM(Orders[Profit])
```

**Total Quantity**
```dax
Total Quantity = SUM(Orders[Quantity])
```

**Total Customers**
```dax
Total Customers = DISTINCTCOUNT(Orders[Customer ID])
```

### 4. Dashboard Development

Designed an interactive Power BI report covering the following business analysis areas:

**1. Executive Summary**
- Overall business performance.
- Key performance indicators (KPIs).
- Summary of important business metrics.

**2. Sales and Profitability Analysis**
- Sales and profit performance.
- Sales distribution and profitability trends.
- Business performance comparisons.

**3. Customer and Segment Analysis**
- Customer performance.
- Revenue contribution by customers.
- Customer segment analysis.

**4. Product and Category Analysis**
- Product category and subcategory performance.
- Best and worst-performing products.
- Sales and profit comparisons.

**5. Shipping Analysis**
- Shipping performance.
- Analysis of shipping-related business information.

**6. Trends and Performance Analysis**
- Sales and profit trends over time.
- Performance comparisons across different business dimensions.
- Identification of significant business fluctuations.

## Power BI Visualizations

The report uses different Power BI visualizations to present business information, including:

- Card
- Line Chart
- Clustered Column Chart
- Slicer
- Matrix
- Donurt Chart
- Stacked Bar Chart
- Cluatered Bar Chart
- Table
- Tree Map
- Stacked Column Chart
- Area Chart
- Scatter Chart
- Decomposition Tree
- Waterfall Chart
 
## Key Business Analysis Areas

The dashboard supports the evaluation of:

- Overall business performance using key performance indicators.
- Customers contributing the most to revenue.
- Best and worst-performing products and subcategories.
- Best and worst-performing countries and regions.
- Seasonal trends and significant fluctuations in sales and profit.
 
 

 
