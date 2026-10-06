# Weather Data Analysis

## Project Overview

This project analyzes daily weather data from **2000 to 2024** using Python. The analysis focuses on temperature and rainfall trends and compares weather conditions across different months.

## Dataset

- **Records:** 91,320
- **Columns:** 12
- **Time Period:** 2000–2024
- **Dataset:** India Daily Weather Data

## Project Workflow

### 1. Data Loading

The weather dataset was loaded into Python using **Pandas**.

### 2. Data Cleaning and Validation

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect temperature records
- Negative rainfall values
- Negative precipitation values

The `date` column was converted into datetime format.

### 3. Temperature Analysis

Year-wise and month-wise average maximum and minimum temperatures were analyzed to identify temperature trends and seasonal variations.

### 4. Rainfall Analysis

Year-wise and month-wise rainfall trends were analyzed to understand variations in rainfall across different periods.

### 5. Monthly Weather Comparison

Weather conditions were compared across all 12 months to identify monthly and seasonal patterns.

### 6. Data Visualization

Graphs were created using **Matplotlib** to present the analysis results clearly.

## Data Cleaning Results

- No missing values were found.
- No duplicate records were found.
- No incorrect temperature records were found.
- No negative rainfall values were found.
- No negative precipitation values were found.

## Key Insights

- **May** recorded the highest average maximum temperature: **36.75**.
- **January** recorded the lowest average minimum temperature: **14.06**.
- **July** recorded the highest average rainfall: **9.69**.
- **January** recorded the lowest average rainfall: **0.33**.
- The dataset does not contain a humidity column, so humidity trends could not be analyzed.

## Visualizations

The project includes the following visualizations:

1. Yearly Temperature Trends
2. Yearly Rainfall Trend
3. Monthly Temperature Comparison
4. Monthly Rainfall Comparison

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Project Files

- `Weather_Data_Analysis_Cognevance.ipynb` – Complete Python analysis notebook
- `india_2000_2024_daily_weather_cleaned.csv` – Cleaned weather dataset
- `Yearly Temperature Trends.png` – Yearly temperature visualization
- `Yearly Rainfall Trend.png` – Yearly rainfall visualization
- `Monthly Temperature Comparison.png` – Monthly temperature visualization
- `Monthly Rainfall Comparison.png` – Monthly rainfall visualization

## Conclusion

The analysis shows clear seasonal variations in temperature and rainfall. The results provide an overview of yearly and monthly weather patterns in the analyzed dataset.
