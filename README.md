# SWYNEX-Data-Cleaning-Preparation

Task 1 submission for the **SWYNEX Technologies Virtual Internship**.

## Objective
The goal of this task is to clean and prepare a raw dataset for analysis by identifying and resolving missing values, duplicates, and incorrect data types.

## Dataset
I used the **Netflix Movies and TV Shows** dataset from Kaggle to perform real-world data cleaning.

## Files in this Repository
* `NetFlix.csv` : The raw, messy dataset.
* `cleaned_netflix_data.csv` : The final, analysis-ready dataset.
* `Data_Cleaning.ipynb` : The Google Colab notebook containing the Python code.

## Cleaning Steps Performed
1. **Removed Duplicates:** Dropped duplicate rows to ensure data accuracy.
2. **Handled Missing Values:** 
   * Filled missing text values in `director`, `cast`, and `country` with 'Unknown'.
   * Dropped rows with missing critical data (`date_added`, `rating`).
3. **Standardized Data Types:** Formatted messy string dates into proper Python DateTime objects.

**Tools Used:** Python, Pandas, Google Colab
