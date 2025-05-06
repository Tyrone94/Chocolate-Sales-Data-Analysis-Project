# 🍫 Chocolate Sales ETL Pipeline Project

This project demonstrates the design and implementation of an end-to-end ETL (Extract, Transform, Load) pipeline using Python for a chocolate sales dataset. The goal is to efficiently prepare raw sales data for analysis by performing data extraction, transformation, and loading in a structured and automated way.

🎯 Project Objectives
Build a reliable ETL pipeline using Python

Clean and transform raw sales data

Generate a structured dataset ready for analysis

Demonstrate proficiency in data engineering and data wrangling practices

🧰 Tools & Technologies Used
Python 3

Pandas – data manipulation

NumPy – numerical operations

Jupyter Notebook – development environment

Matplotlib / Seaborn – for potential visualizations

OS and Glob – for file handling during extraction

ETL functions – to modularize code

🔁 ETL Pipeline Steps
1. Extract
Loaded chocolate sales data from CSV files using pandas.read_csv()

Used the os and glob libraries to locate and manage file paths

2. Transform
Cleaned the data: removed nulls, fixed date formats, ensured consistent column names

Performed feature engineering (e.g., extracted month from OrderDate)

Converted data types for consistency (dates, floats, etc.)

Generated new columns to improve analysis (e.g., Revenue, Average Order Value)

3. Load
Loaded the cleaned and transformed dataset into a structured DataFrame

Saved final output to a CSV file named Cleaned_Chocolate_Sales.csv for future use in analytics or BI tools


✅ Outcome
This project showcases the practical implementation of data engineering concepts and Python scripting in building ETL pipelines. It prepares the data for deeper analysis and serves as a strong foundation for integrating with dashboards, reporting tools, or advanced analytics projects
