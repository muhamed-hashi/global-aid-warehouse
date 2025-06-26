# Global Aid Disbursement Data Warehouse

This project analyzes 2023 international aid flows using data from the International Aid Transparency Initiative (IATI), enriched with Human Development Index (HDI) data. We built a dimensional data warehouse and used advanced SQL queries to uncover trends, mismatches, and insights into global development financing. The final enriched dataset was loaded into **Google BigQuery**, enabling scalable, cloud-based querying and dashboard integration for interactive data analysis.


## Features
- Dimensional modeling using a star schema
- ETL pipeline with PySpark for data transformation
- Integration of HDI data to evaluate equity in aid allocation
- Analytical SQL queries using CUBE, window functions, and time-series analysis

## Key Analyses
- Aid disbursement patterns by HDI and sector
- Top recipient organizations by country
- Finance type and flow type breakdown
- Volatility and consistency in aid distribution across countries and years

## Tools Used
- PySpark
- SQL (Google BigQuery)
- Data visualization (matplotlib, seaborn)

## Authors
- Muhamed Hashi
