🛒 Zepto SQL Data Analysis Project
📌 Overview

This project focuses on analyzing Zepto product data using SQL to answer real-world business questions. The dataset was sourced from a CSV file and loaded into a PostgreSQL database, where various exploratory, cleaning, and analytical queries were performed. The goal is to derive actionable insights related to product availability, pricing, discounts, and inventory patterns.

📂 Dataset

Source: Public / Practice dataset

Format: CSV

Description: Product-level data including category, pricing, discounts, stock availability, and quantity details

Use Case: SQL practice and business-oriented data analysis

🛠 Tools & Technologies

PostgreSQL – Database management

SQL – Data exploration, cleaning, and analysis

CSV – Raw data source

🔍 Project Workflow
1️⃣ Data Loading

Imported CSV data into PostgreSQL

Created structured table schema with appropriate data types

Verified data integrity and row counts

2️⃣ Data Exploration

Checked total number of records

Previewed sample data

Identified distinct product categories

Analyzed in-stock vs out-of-stock products

Detected duplicate product names with multiple SKUs

3️⃣ Data Cleaning

Identified and removed invalid price records (e.g., zero MRP)

Handled missing and inconsistent values

Standardized pricing units for accurate analysis

Ensured clean, analysis-ready data

4️⃣ SQL Analysis

Wrote SQL queries to answer key business questions, including:

Category-wise product distribution

Discount patterns across products

Stock availability analysis

Pricing comparisons (MRP vs discounted price)

Inventory insights using aggregation and filtering

📈 Key Insights

Identified categories with the highest product count

Highlighted products with maximum discounts

Analyzed stock availability trends

Detected pricing inconsistencies and anomalies

📁 Repository Structure
zepto-sql-analysis/
│── data/
│   └── zepto.csv
│── sql/
│   ├── table_creation.sql
│   ├── data_cleaning.sql
│   └── analysis_queries.sql
│── README.md

▶️ How to Run the Project

Clone this repository

Create the database and table using table_creation.sql

Load the CSV data into PostgreSQL

Run SQL queries from the sql/ folder to explore and analyze data

🎯 Key Takeaways

Demonstrates strong SQL fundamentals

Applies SQL to real-world business scenarios

Showcases data cleaning, exploration, and analysis skills

Recruiter-ready project for Data Analyst roles
