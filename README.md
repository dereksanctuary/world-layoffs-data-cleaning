# world layoffs data cleaning (sql project)

a real-world sql data cleaning project focused on transforming and standardizing global tech layoff data using industry-standard practices.

this project demonstrates practical use of sql for preparing raw datasets for analysis, reporting, and visualization.

---

## why?

raw datasets are rarely clean. this project shows how to:

- remove duplicates  
- standardize inconsistent text values  
- handle null values  
- split and format date columns  
- prepare structured data for analytics  

reflects data engineering and analytics workflows used in industry.

---

## features

- duplicate row detection & removal  
- trimming & standardization of text fields  
- country name normalization  
- date formatting
- null value handling  
- staging tables for safe transformations  
- window functions for row partitioning  

---

## tools used

- sql  
- common table expressions (cte)  
- window functions  
- string functions  
- staging tables  

---

## project structure

world-layoffs-data-cleaning/
│
├── layoffs.csv
├── layoffs_data_cleaning.sql
└── README.md

---

## workflow

1. imported raw layoffs dataset  
2. created a staging table to preserve original data  
3. removed duplicate rows using window functions  
4. standardized company names, locations, and countries  
5. converted date strings into sql date format  
6. cleaned and normalized all columns  
7. output clean dataset ready for analysis  

---

## demonstrates

- real-world data cleaning workflows  
- strong sql fundamentals  
- production-style staging pipelines  
- analytical data preparation  
- attention to data integrity  

---

## future improvements

- visualization using tableau or power bi  
- automated cleaning pipelines  
- job trend forecasting  
- industry comparison dashboards  

---
