# Near-Real-Time-Data-Warehouse-Prototype

This GitHub project aims to design, implement, and analyze a near-real-time Data Warehouse (DW) prototype

# Key Features:

## Near-Real-Time DW:

Implementing a near-real-time DW to reflect customers' transactions from Data Sources (DSs) as soon as they appear, enabling rapid analysis of shopping behaviors.

## Enrichment with Master Data:

Incomplete customer data from transactions is enriched in the transformation layer of ETL using Master Data (MD), facilitating comprehensive analysis.

## MESHJOIN Algorithm Implementation:

The project utilizes the MESHJOIN algorithm, introduced by Polyzotis, to perform the Stream-Relation join operation efficiently during the transformation phase of ETL.

## Star Schema Modeling:

Utilizing the star schema data modeling technique to map multidimensional decision support data into a relational database, allowing for easy implementation of multidimensional data analysis.

## DW Analysis:

Conducting OLAP queries to analyze the DW, including determining top-performing stores, forecasting supplier performance, and presenting sales analytics for products and suppliers across different time periods.

## Comprehensive Tasks Break-Up:

The project delineates tasks such as identifying dimension tables, implementing MESHJOIN algorithm, conducting DW analysis, and writing a comprehensive project report.

# Deliverables:

### createDW SQL Script:

A script file to create star-schema for the DW, ensuring the removal of pre-existing schema.

### meshJoin Eclipse Project:

An Eclipse-based Java project implementing the MESHJOIN algorithm, capable of dynamically taking database credentials at execution time.

### queriesDW SQL Script:

A script file containing sql queries for analysis of data

### Project Report:

A comprehensive document detailing project overview, DW schema, MESHJOIN algorithm implementation, shortcomings in MESHJOIN, and key learnings.

# How to Run:

1. Run the createDW sql script file on MySql. This will create fact table and dimension tables of the datawarehouse
2. Run java file meshjoin on eclipse
3. Enter you MySQL username and password
4. This will run and execute the ETL process
