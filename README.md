# sales-data-cleaning
Cleaning and standardizing a messy sales Excel file using Python (pandas): removing duplicates, unifying dates and city names, and handling missing values.
# Sales Data Cleaning

A Python (pandas) notebook that cleans a messy sales Excel file.

## What it does
- Removes duplicate rows
- Standardizes dates to YYYY-MM-DD
- Unifies city names (Arabic + English -> English)
- Fills missing prices from the same product
- Flags missing quantities instead of guessing them
- Adds an order total column and a short summary sheet

## Files
- `cleaned_data.ipynb`: the cleaning code
- `cleaned_sales.xlsx`: the cleaned output

Note: the input Excel file is not included. Place your own sales file next to the notebook and update the file name in the first cell.

## Tools
Python, pandas, openpyxl
