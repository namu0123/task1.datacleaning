# Task 1: Data Cleaning and Preprocessing

## Objective
The objective of this task is to clean and prepare a raw dataset by handling missing values, removing duplicates, standardizing text and date formats, and ensuring proper data types. The cleaned dataset is ready for analysis or further processing.

## Tools Used
- **Python (Pandas)** – for automated data cleaning.
- **Excel** – for manual cleaning and formula-based automation.

## Steps Performed

1. **Identify and Handle Missing Values**
   - Checked for null values.
   - Filled missing text values with `Unknown` and numeric values with `0`.
   - Dropped rows with missing critical data when necessary.

2. **Remove Duplicate Rows**
   - Removed duplicate entries to ensure unique records.

3. **Standardize Text Values**
   - Capitalized names and other text fields using `PROPER` function in Excel.
   - Standardized gender values (`M`/`F` → `Male`/`Female`).
   - Standardized country names (e.g., `USA`, `Us` → `United States`).

4. **Convert Date Formats**
   - Converted all date columns to consistent `dd-mm-yyyy` format.

5. **Rename Columns**
   - Renamed columns to lowercase with underscores, e.g., `Customer Name` → `customer_name`.

6. **Fix Data Types**
   - Ensured numeric columns are of integer/float type.
   - Converted date columns to proper date format.

7. **Save Cleaned Dataset**
   - Saved final cleaned dataset as `cleaned_dataset.csv`.
   - Created an Excel template with formulas for automatic cleaning.

## Files Included

- `data_cleaning.py` – Python script for automated cleaning.
- `cleaned_dataset.csv` – Final cleaned dataset.
- `Excel_Template.xlsx` – Excel version with automatic cleaning formulas.
- `raw_dataset.csv` – Original dataset (optional).
- `screenshots/` – Screenshots showing cleaning steps in Excel or Python (optional).

## Summary
The dataset is now cleaned, standardized, and ready for analysis. All missing values, duplicates, inconsistent text, and date formats have been handled to ensure high-quality data for future tasks.
