# 🚢 Titanic ETL Pipeline

## 🔹 Overview
This project implements an **ETL (Extract, Transform, Load) pipeline** for the **Titanic dataset**. The goal is to clean, transform, and load data for analysis, making it ready for modeling and visualization.

---

## 📚 Steps Covered
- **Extract:** Load raw Titanic CSV data from local files.  
- **Transform:**  
  - Handle missing values  
  - Convert categorical features into numeric codes  
  - Create derived features (like family size, title, etc.)  
- **Load:** Insert cleaned and transformed data into a database (Supabase/PostgreSQL).  
- **Validate:** Check for nulls, duplicates, and ensure data consistency.  
- **Analyze:** Generate summary statistics and visualizations like survival rates, passenger class distributions, and age histograms.  

---

## 💻 Code / File Structure
ETL-Titanic/
├── data/
│ ├── raw/ # Original CSV files
│ ├── staged/ # Transformed data
│ └── processed/ # Analysis outputs
├── extract.py # Extract raw data
├── transform.py # Transform data
├── load.py # Load data into database
├── validate.py # Validate transformed data
├── etl_analysis.py # Generate metrics and visualizations
└── README.md
