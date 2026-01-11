# Walmart Sales Data Analysis  
### End-to-End SQL + Python Analytics Project

## Overview
This project is an end-to-end data analytics solution built to extract business insights from Walmart sales data. It demonstrates a complete analytics workflow using **Python for data processing**, **SQL for querying**, and **relational databases** for structured storage and analysis.

The project focuses on answering real-world business questions around revenue trends, product performance, customer behavior, and profitability.

---

## Tech Stack
- **Programming:** Python 3.8+
- **Databases:** MySQL, PostgreSQL
- **Libraries:** Pandas, NumPy, SQLAlchemy
- **DB Connectors:** psycopg2, mysql-connector-python
- **Tools:** VS Code, Jupyter Notebook
- **Data Source:** Kaggle – Walmart Sales Dataset

---

## Project Workflow

### 1. Environment Setup
- Created a structured workspace using VS Code
- Organized folders for data, SQL scripts, notebooks, and documentation
<img width="302" height="359" alt="Screenshot 2026-01-12 at 01 00 35" src="https://github.com/user-attachments/assets/62dc35bd-1ef4-41d1-b795-54e8b3a73706" />


### 2. Data Acquisition
- Downloaded Walmart sales data using the Kaggle API
- Stored raw files in the `data/` directory

### 3. Data Exploration
- Loaded data into Pandas DataFrames
- Performed initial exploration using `.info()`, `.describe()`, and `.head()`

### 4. Data Cleaning
- Removed duplicate records
- Handled missing values based on relevance
- Standardized data types (dates, numeric fields)
- Cleaned and formatted currency values

### 5. Feature Engineering
- Created a **Total Transaction Amount** feature (`unit_price × quantity`)
- Prepared data for efficient SQL aggregation

### 6. Database Integration
- Loaded cleaned data into **MySQL and PostgreSQL**
- Automated table creation using SQLAlchemy
- Validated data using SQL queries
<img width="1054" height="540" alt="Screenshot 2026-01-12 at 01 01 39" src="https://github.com/user-attachments/assets/7fef0f56-45d4-4c24-863a-f419e2c25270" />

### 7. SQL Analysis
Used advanced SQL queries to answer key business questions:
- Revenue trends by branch and product category
- Best-selling and most profitable products
- Sales performance by city, time, and payment method
- Peak sales periods and customer purchasing behavior
- Profit margin analysis by branch and category
<img width="356" height="618" alt="Screenshot 2026-01-12 at 01 02 43" src="https://github.com/user-attachments/assets/e6c5eeba-bfe1-48c2-bf6c-7a9da3856f29" />

---

## Project Structure
data/ # Raw and cleaned datasets
sql_queries/ # SQL scripts for analysis
notebooks/ # Jupyter notebooks for Python analysis
main.py # Data cleaning and database loading script
requirements.txt # Python dependencies
README.md # Project documentation


---

## Key Insights
- Identified top-performing branches and product categories
- Highlighted high-profit regions and products
- Discovered customer behavior trends such as peak shopping hours and payment preferences

These insights support data-driven decision-making in sales and operations.

---

## Getting Started

1. Clone the repository
bash
git clone <repository-url>
2. Install dependencies

pip install -r requirements.txt


3.Configure Kaggle API and download the dataset

4.Run Python scripts to clean and load data

5.Execute SQL queries or explore notebooks for insights

## Future Enhancements

Integration with Tableau or Power BI dashboards

Additional datasets for deeper analysis

Automation of the data pipeline for near real-time analytics

License

This project is licensed under the MIT License.

Acknowledgments

Dataset: Kaggle – Walmart Sales Dataset

Inspiration: Walmart sales and supply chain case studies









