# ETL-Mini-Pipeline

## Objective
Create a simple ETL process that extracts raw data, performs cleaning and transformations, and loads structured outputs into CSV files and a SQLite database.

---

## Tech Stack
- Python  
- pandas  
- sqlite3  
- Jupyter Notebook / Colab  

---

## Files in Repository
- `Churn_Modelling.csv` → Raw dataset  
- `processed_data.csv` → Cleaned master data  
- `customers.csv` → Customer information  
- `accounts.csv` → Account details  
- `churn.csv` → Churn status  
- `database.sqlite` → Database with tables  
- `task14_etl.ipynb` → ETL pipeline implementation  

---

## ETL Steps
**Extract:** Load the original CSV file.  
**Transform:** Remove duplicates, handle missing values, standardize columns, create derived features.  
**Load:** Save processed data, generate separate tables, and insert them into SQLite.

---

## How to Run
Open `task14_etl.ipynb` and run the cells in order.  
All output files will be generated automatically.

---

## Outcome
Shows understanding of data cleaning, transformation, and loading for analytics workflows.

---
