# retail-data-cleaning-pandas
# Retail Data Ingestion, Cleaning & Preprocessing with Pandas

## Project Overview
This project demonstrates data ingestion, data quality assessment, cleaning, and preprocessing of retail order data using Python and Pandas.

## Objectives
- Identify missing values and duplicate records.
- Standardize inconsistent text and data types.
- Validate dates, quantities, prices, and discount percentages.
- Handle invalid records and missing values.
- Identify potential outliers using the IQR method.
- Create date-based features and sales calculations.
- Export the cleaned dataset as a CSV file.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook
- GitHub

## Project Files
- `retail_data_cleaning_complete.ipynb` — analysis and preprocessing notebook
- `retail_data_cleaning_complete.py` — Python script
- `clean_dataset.csv` — cleaned dataset
- `data_quality_report.csv` — before-and-after quality summary

## Results
The notebook reports row counts, missing values, duplicate records, data types, and the resulting engineered features. Final results should be updated after running the notebook on the source dataset.

## Limitations
The current dataset has nine source columns. Reliable profit-margin calculation requires additional cost or profit information. The project does not fabricate missing data or create artificial rows to meet a row-count target.
