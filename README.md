## Project Overview

This ETL pipeline idea originated from a project I stumbled upon on LinkedIn about a year ago. The original project was designed for an imaginary startup and from what I remember the goal was to create a database using a star schema, featuring 1 fact table and 4 dimension tables.

All raw data for this project is stored in JSON files. The pipeline extracts information from these JSON files using the pandas Python library and inserts the data into the structured database schema.


I decided to build this project after completing a course last semester called "Business Intelligence and Analytics". The course provided me with the foundational skills and knowledge to understand and implement ETL pipelines effectively, and this project was a great way to put those concepts into practice.



## Prerequisites

need to install:

- psycopg2
- ipython-sql
- pandas
- numpy

## Getting Started

First of all, to run your ETL pipeline, we need to create the database. 
All the information about the database, create and insert statements  you can find it in **create_tables.py / sql_queries.py**

`python create_tables.py`

This will use all the information specified in your create_tables.py file, like username, password, database, and queries etc.
After that, will execute **CREATE STATEMENTS** for all your tables.

execute your ETL pipeline. 

`python etl.py`







