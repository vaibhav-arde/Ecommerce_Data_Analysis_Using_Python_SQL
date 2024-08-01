# Ecommerce_Data_Analysis_Using_Python_SQL
E-commerce Data Analysis with SQL and Python: Comprehensive analysis of e-commerce sales, customer behavior, and product performance. Leveraging SQL for data extraction and Python for advanced analytics and visualisation.


## Ecommerce Data
Get all data (csv files) from below Kaggle url:
link : `https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv`


## Virtual environment
Create virtual environment: 

*mac/linux :* `python3 -m venv .venv`

*windows* `python -m venv .venv`

Activate virtual env:

*mac/linux :* `source .venv/bin/activate`

*windows* `.venv\Scripts\activate`


## Libraries:
Execute command in terminal to install all libraries :

`pip install -r requirements.txt`

or 

Install libraries one by one:

- Pandas : `pip install pandas`

- mysql connctor : `pip install mysql-connector-python`

- matplotlib : `pip install matplotlib`

- seaborn : `pip install seaborn`

- python-dotenv : `pip install python-dotenv`


## MYSQL
It is assumed that one has mysql installed in machine and can use mysql workbench

using workbench create database named : `ecommerce`

## Table creation in DB
To create tables in mysql use `csv_to_sql.py`
- Update its credentials to connect with mysql
    * Create `.env` file and update it with your actual value.
        * MYSQL_HOST=your_host
        * MYSQL_USER=your_user
        * MYSQL_PASSWORD=your_password
        * MYSQL_DB=your_database
- Update folder path where data is downloaded from Kaggle
- Execute `python csv_to_sql.py`


## Now you are all set to go ahead and execute sql queries using python on the ecommerce data.
