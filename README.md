# Data Cleaning and Preprocessing Task

## Objective

The objective of this task is to clean and preprocess a raw dataset by handling missing values, checking duplicate records, fixing inconsistent text formats, converting date columns, renaming column headers, and correcting data types.

## Dataset Used

Netflix Movies and TV Shows Dataset

## Tools Used

* Python
* Pandas
* Jupyter Notebook

## Dataset Information

* Total Rows: 8807
* Total Columns: 12

## Missing Values Found

* director: 2634 missing values
* cast: 825 missing values
* country: 831 missing values
* date_added: 10 missing values
* rating: 4 missing values
* duration: 3 missing values

## Cleaning Steps Performed

1. Loaded the dataset using Pandas
2. Checked the dataset structure using head(), info(), and isnull()
3. Identified missing values in multiple columns
4. Filled missing values in:

   * director with "Unknown"
   * cast with "Not Available"
   * country with "Unknown"
   * rating with "Not Rated"
   * date_added with "01-01-2000"
5. Converted the date_added column into datetime format
6. Renamed all column names into lowercase
7. Replaced spaces in column names with underscores
8. Standardized text values in type and country columns
9. Checked data types of all columns
10. Checked duplicate rows
11. Removed duplicate rows if present
12. Saved the final cleaned dataset as cleaned_netflix_titles.csv

## Summary

The dataset was successfully cleaned and prepared for analysis. Missing values were handled, text values were standardized, date formats were converted, and data types were verified. No duplicate rows were found in the dataset.

## Output

Generated cleaned dataset file:
cleaned_netflix_titles.csv
