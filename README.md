# SWYNEX-INTERNSHIP


# Netflix Data Cleaning Project

## Project Overview

This project focuses on identifying and correcting data quality issues in the Netflix Movies and TV Shows dataset. The dataset was analyzed and cleaned using Python and Pandas to improve data accuracy, consistency, and usability.

## Objectives

- Identify missing values in the dataset.
- Detect and remove duplicate records.
- Correct inappropriate data types.
- Standardize inconsistent values and formatting.
- Prepare a clean dataset for further analysis.

## Dataset

The dataset contains information about Netflix movies and TV shows, including titles, directors, cast, countries, release years, ratings, durations, and genres.

**Source:** [Netflix Movies and TV Shows Dataset – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Tools & Technologies

- Python
- Pandas
- Google Colab
- GitHub

## Data Cleaning Process

1. **Missing Values:** Identified missing values and handled them appropriately. Missing categorical information such as director, cast, country, and rating was replaced with `Unknown`.
2. **Duplicate Records:** Detected and removed duplicate rows to avoid repeated records.
3. **Data Type Correction:** Converted date columns into datetime format and release year into an integer data type.
4. **Value Standardization:** Removed extra whitespace and standardized categorical values such as Movie and TV Show.
5. **Duration Cleaning:** Extracted duration values and units into separate columns for easier analysis.
6. **Validation:** Verified the cleaned dataset for remaining duplicates, missing values, and data type issues.

## Project Files

- Netflix-Movies, Shows, etc.. Cleaned datasets

## Results

The dataset was processed to improve data quality by handling missing information, removing duplicate records, correcting data types, and standardizing inconsistent values.

## Conclusion

This project demonstrates practical data cleaning skills using Python and Pandas. The cleaned dataset is more consistent and suitable for exploratory data analysis and further data-driven insights.

---

**Internship Task:** Data Cleaning and Preprocessing
**Project Type:** Data Analytics









# Netflix Movies and TV Shows – Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset after completing the data cleaning and preprocessing task. The objective is to analyze content distribution, release trends, ratings, countries, and genres to identify meaningful patterns and insights.

## Dataset Summary
- Total Records: 8,807
- Movies: 6,131
- TV Shows: 2,676
- Total Columns: 12

## Key Findings
1. Movies represent approximately 69.6% of the dataset, while TV Shows account for 30.4%.
2. 2018 was the peak release year in the dataset.
3. TV-MA is the most frequently occurring rating.
4. The United States is the leading country based on title counts.
5. International Movies is the most frequent genre/category.

## Visualizations
- Movies vs TV Shows distribution
- Content release-year trend
- Ratings distribution
- Top 10 content-producing countries
- Top 10 genres

## Tools Used
Python, Pandas, Matplotlib, Google Colab, Microsoft Excel

## Conclusion
The analysis reveals that Netflix's catalog contains a higher proportion of movies than TV shows. It also highlights release-year patterns, audience rating distributions, country representation, and popular content categories. The visualizations make these patterns easier to understand and support data-driven interpretation.

**Internship Task:** Exploratory Data Analysis (EDA)  
**Project Type:** Data Analytics

