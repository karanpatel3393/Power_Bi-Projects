# Sales Insight Dashboard using Power BI

## Project Overview

This project involves building a Power BI dashboard to provide sales insights for AtliQ Hardware, a company that delivers computer hardware and peripherals across India. The goal was to address the challenges faced by the Sales Director in understanding the business's performance and making data-driven decisions.

The project was inspired by the Code Basics YouTube Playlist and aims to showcase the power of visualizing data for better decision-making.

## Problem Statement

AtliQ Hardware’s sales are declining, and the Sales Director faces difficulties in understanding performance metrics from Excel files. Human inefficiency in consuming numerical data has led to frustration and suboptimal decision-making.

## Solution

A Power BI dashboard was developed to:

1. Convert raw data into visual representations.

2. Provide actionable insights to improve sales and profit margins.

3. Empower stakeholders to make data-driven decisions.

## AIMS Grid

- **Purpose:** To deliver a comprehensive sales insights dashboard.

- **Stakeholders:** Sales Director, Regional Managers, Data Analysts.

- **End Result:** A Power BI dashboard visualizing sales trends, market performance, customer contributions, and product insights.

## Success Criteria:

- Improved understanding of sales performance.

- Identification of underperforming regions and products.

- Better-informed decision-making by stakeholders.

## Steps Followed

**1. Project Planning:** Used AIMS Grid to define project goals.

**2. Data Retrieval:** Used MySQL to extract data from the database into Power BI.

**3. Data Cleaning:** Cleaned and prepared data in Power Query.

**4. ETL Process:** Extracted, transformed, and loaded data.

**5. Currency Conversion:** Standardized all transaction currencies.

**6. Data Validation:** Ensured data accuracy and consistency.

**7. Data Modeling and Visualization:** Created relationships and developed interactive visuals.

## Customizations

- Replaced the original products table with a self-modified table to resolve ‘(blank)’ issues, adding new products (Prod280 to Prod339).

- Enhanced the sales_transaction table by merging additional fields such as profit margin and cost price.

## Insights

**1. Revenue and Profit Metrics:**

   - **Total revenue (4 years):** ₹985M

   - **Total profit margin:** ₹24.7M (2.5%)

   - **Total sales quantity:** ₹2M

**2. Market Performance:**

   - **Largest market:** Delhi NCR (₹520M revenue, 2.3% profit margin).

   - **Highest profit margin:** Bhubaneshwar (10.48% in 2020).

   - **Lowest profit margin:** Bengaluru (-20.8%).

**3. Top Customers:**

   - **Electricalsara Stores:** ₹413M revenue (4 years).

**4. Product Insights:**

   - **Top product:** Prod318 (₹69M revenue).

   - **Distribution vs Own Brand revenue:** ₹494M each.

 **5. Revenue Trends:**

   - Significant decline in June 2020.

   - Lowest profit margin in April 2020.

## Key Learnings

- Understanding real-world business datasets.

- Writing analytical queries in MySQL.

- Connecting and transforming data in Power BI.

- Practical usage of DAX functions and measures.

- Creating analytical visuals and actionable reports.

## Final Result

**Dashboard Features:**

**1. KPI Page:** Showcasing key metrics like total revenue, profit margins, and sales trends.

**2. Market Analysis:** Regional breakdown of revenue and profit contributions.

**3. Customer Insights:** Top customers driving revenue.

**4. Product Performance:** Revenue and profit by product type.

## Technologies Used

**- MySQL:** Data extraction and analysis.

**- Power BI:** Data visualization and dashboard creation.

**- Power Query**: Data cleaning and transformation.

**- DAX (Data Analysis Expressions):** Measures and calculations.

## How to Use

- Clone this repository to your local machine.

- Open the Power BI file (Sales_Insight_Dashboard.pbix).

- Ensure the database connection settings are correctly configured.

- Explore the interactive dashboard to analyze insights.

## Future Improvements

- Automating data refresh using Power BI Service.

- Adding more KPIs and deeper drill-through options.

- Incorporating machine learning models for predictive analytics.

