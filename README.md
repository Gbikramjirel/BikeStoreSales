# BikeStoreSales
I worked with a BikeStores sales dataset where I cleaned and joined multiple tables, then designed an interactive dashboard that highlights key sales patterns and business trends in a visually compelling way.

# Project Overview

This project demonstrates the end-to-end process of building and analyzing a relational database system for a retail business scenario. Using the BikeStores dataset, I designed schemas, created tables, populated them with sample data, performed multi-table joins, and generated insights through SQL queries and Tableau visualizations.

The goal was to practice data modeling, ETL concepts, and business analytics by replicating real-world workflows: from database design to KPI reporting.

# Database Schema
The project consists of two schemas:

1. Production Schema
- Categories – defines product categories.
- Brands – stores brand information.
- Products – details of products, linked to categories and brands.
- Stocks – inventory levels per store and product.

2. Sales Schema
- Customers – customer personal and location details.
- Stores – store details.
- Staffs – employees, including manager–employee hierarchy.
- Orders – customer orders with statuses and dates.
- Order_Items – line-level details of products per order.

Relationships were enforced with primary keys, foreign keys, and cascade rules for referential integrity.

# Data Loading & Transformation
- Fed sample data into all the tables including brands, categories, products, customers, stores, and staff.
- Merged first_name and last_name into a full name column for both customers and staff.
- Performed multiple SQL joins across schemas (e.g., orders + customers + stores + products + staffs) to extract sales, revenue, and product-level insights.

# Business KPIs
Using Tableau, I built dashboards to highlight key business performance metrics, such as:
- Total Revenue & Sales Trends
- Top-Selling Products and Categories
- Revenue Contribution by Store and Region
- Salesperson Performance
- Customer Purchase Patterns

#Tableau Dashboard
The dashboard includes:
- Clustered Column Bar Graphs – revenue trends across categories.
- Clustered Bar Charts – sales performance by staff and stores.
- Pie Charts – revenue breakdown by product categories.
- Line Graphs – monthly sales trends over time.

Tableau workbook: Bikesales Dashboard.twbx

# Tech Stack
- SQL (MySQL) – schema design, data insertion, joins, aggregations.
- Excel – refined data preparation and validation.
- Tableau – dashboard creation and KPI visualization.

# How to Use
1. Clone the repository.
2. Run the schema creation file (Schema Design.sql) to build the database.
3. Load the sample data (BikeStores Sample Database - load data.sql).
4. Use the query file (BikeStores Combine Table.sql) to generate combined datasets for analysis.
5. Open Bikesales Dashboard.twbx in Tableau to explore the KPIs and visualizations.

# Key Learnings
- Designing normalized relational schemas with foreign key dependencies.
- Applying joins and aggregations across multiple schemas for business reporting.
- Building interactive Tableau dashboards to communicate insights effectively.
