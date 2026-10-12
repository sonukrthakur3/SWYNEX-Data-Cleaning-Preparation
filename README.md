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


# SWYNEX - Task 2: Exploratory Data Analysis (EDA) & Visualization

This repository contains my submission for **Task 2** of the **SWYNEX Technologies Virtual Internship**.

## Objective
Perform exploratory data analysis on the cleaned Netflix dataset to calculate summary statistics, identify key trends/patterns/anomalies, generate visual charts, and document useful insights.

## Files in this Repository
* `cleaned_netflix_data.csv`: Cleaned dataset from Task 1.
* `task2_eda.ipynb`: Google Colab / Jupyter Notebook containing the Python code for EDA and data visualization.
* `chart1_content_type.png`: Pie chart showing Movies vs TV Shows distribution.
* `chart2_yearly_trend.png`: Line chart showing catalog growth over the years.
* `chart3_top_countries.png`: Bar chart of top content-producing countries.
* `chart4_ratings.png`: Bar chart showing content rating distributions.

## Key Statistics & Insights
1. **Content Type Distribution:** Movies make up **69.1%** of the catalog, while TV Shows comprise **30.9%**.
2. **Peak Addition Years:** Content acquisition skyrocketed between 2016 and 2019, peaking in **2019 with over 2,100 additions**.
3. **Geographic Distribution:** The **United States** (2,546 titles) and **India** (923 titles) are the leading producers of content on the platform.
4. **Target Audience:** Over **60%** of titles are rated **TV-MA** or **TV-14**, showing a clear focus on mature and young-adult demographics.
5. **Genre Trends:** **International Movies and Dramas** dominate as the most prevalent genres on Netflix.

**Tools Used:** Python, Pandas, Matplotlib, Seaborn, Google Colab
