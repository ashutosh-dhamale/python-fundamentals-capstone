Python Data Wrangling & Business Logic — SkilloVilla Capstone
Overview

A Pandas-based data engineering exercise: building relational datasets from raw tables, cleaning and merging them, and applying conditional business logic — all without pre-built libraries beyond NumPy/Pandas.

What this project does
Constructs three DataFrames (Employee, Project, Seniority) from raw source tables and exports them to CSV

Imputes missing Project Cost values using a loop-based running average

Splits and cleans name fields (First/Last Name, honorific prefixes)

Merges all three datasets into a single unified DataFrame on shared ID keys

Applies conditional business rules:

5% completion bonus for finished projects

Seniority-level demotion for failed projects, promotion by age threshold

Aggregates total project cost per employee via groupby

Filters records using string pattern matching

Key result

Total project cost per employee, aggregated across 14 project records for 5 employees, ranged from ₹26.8L to ₹95L — validated against source records after all transformations.

Tools

Python, Pandas, NumPy, Jupyter Notebook
