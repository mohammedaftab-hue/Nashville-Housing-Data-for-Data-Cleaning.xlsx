Overview

This project focuses on cleaning and transforming a real-world housing dataset using SQL. The Nashville Housing dataset contained missing values, duplicate records, inconsistent formats, and unstructured data that required cleaning before analysis. The goal was to create a reliable, analysis-ready dataset for reporting and business insights.

🎯 Project Objectives
Clean and standardize housing data.
Handle missing and null values.
Remove duplicate records.
Standardize date formats.
Split and transform address fields.
Improve overall data quality for analysis.
🛠 Technologies Used
SQL Server
SQL Queries
Excel
Data Cleaning Techniques
🔍 Data Cleaning Process
1. Data Exploration
Reviewed dataset structure and column types.
Identified missing values and inconsistencies.
Assessed data quality issues.
2. Standardized Date Format

Converted inconsistent date formats into a standardized format to improve reporting accuracy and query performance.

3. Populated Missing Property Addresses

Used self-joins to populate missing property addresses by matching records with the same parcel identifier.

4. Split Address Columns

Separated address fields into:

Property Address
Property City
Owner Address
Owner City
Owner State

This improved usability and analysis flexibility.

5. Standardized Categorical Values

Converted inconsistent values such as:

Y → Yes
N → No

to maintain consistency across the dataset.

6. Removed Duplicate Records

Used ROW_NUMBER() and Common Table Expressions (CTEs) to identify and remove duplicate entries while preserving unique records.

7. Dropped Unnecessary Columns

Removed redundant columns after transformation to improve dataset efficiency and readability.

📊 SQL Concepts Demonstrated
Joins
Self Joins
CTEs (Common Table Expressions)
Window Functions
ROW_NUMBER()
String Functions
CASE Statements
Data Transformation
Data Cleaning
📈 Key Results
Eliminated duplicate records.
Filled missing property information.
Improved consistency across address and categorical fields.
Created a clean and structured dataset ready for analysis.
💡 Business Value

Clean housing data enables:

Accurate property market analysis.
Reliable reporting and visualization.
Better investment and pricing decisions.
Improved data governance practices.
🛠 Skills Demonstrated
SQL Data Cleaning
Data Transformation
Data Quality Assessment
Window Functions
Data Validation
Problem Solving
Analytical Thinking
📂 Repository Structure
Nashville-Housing-Data-Cleaning/
│
├── Nashville Housing Data for Data Cleaning.xlsx
├── Portfolio Project - Data Cleaning.sql
├── Cleaned_Housing_Data.csv
├── README.md
└── Documentation.md
🚀 Key Learnings
Handling real-world messy datasets.
Using SQL to automate cleaning workflows.
Applying window functions for deduplication.
Transforming raw data into analysis-ready datasets.
