# Unemployment Analysis in India

## Project Overview

This project focuses on analysing unemployment trends in India using Python. It explores regional variations in unemployment rates, monthly trends, state-wise comparisons, and changes in unemployment before and after the COVID-19 pandemic.

The objective is to use data analysis and visualization techniques to identify patterns in unemployment and better understand the changes in India's employment landscape.

## Objectives

- Analyse average unemployment rates across different regions of India.
- Identify monthly trends and fluctuations in unemployment.
- Compare unemployment trends across selected states.
- Examine relationships between employment-related indicators.
- Compare average unemployment rates before and after March 2020.

## Technologies Used

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and cleaning
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Google Colab** – Development environment

## Dataset

**Dataset:** Unemployment in India

**Source:** [Kaggle – Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)

The dataset contains unemployment and employment-related information, including:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

The original dataset contained 768 rows. After removing completely empty rows and cleaning the column names, 740 records were retained for analysis.

## Data Cleaning and Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected the dataset structure and identified missing values.
3. Removed rows containing entirely missing values.
4. Cleaned column names by removing unwanted spaces.
5. Converted the Date column into datetime format.
6. Verified the cleaned dataset before performing analysis.

## Exploratory Data Analysis

The project includes the following analyses:

1. **Regional Unemployment Analysis:** Calculated and visualized the average unemployment rate across Indian regions.
2. **Monthly Trend Analysis:** Examined changes in the average unemployment rate over time.
3. **State-wise Comparison:** Compared unemployment trends in Maharashtra, Uttar Pradesh, and Tamil Nadu.
4. **Top 10 Regions:** Identified the ten regions with the highest average unemployment rates.
5. **Correlation Analysis:** Used a heatmap to examine relationships between unemployment rate, estimated employment, and labour participation rate.
6. **Pre-COVID vs Post-COVID Analysis:** Compared average unemployment rates before and after March 2020.

## Key Findings

- Tripura recorded the highest average unemployment rate at approximately **28.35%**.
- Meghalaya recorded the lowest average unemployment rate at approximately **4.80%**.
- Among the three selected states, Tamil Nadu showed the sharpest increase in unemployment around April–May 2020.
- The monthly analysis showed a significant rise in unemployment during April and May 2020.
- The average unemployment rate increased from **9.51% before March 2020** to **17.77% from March 2020 onwards**.

## Conclusion

The analysis revealed considerable regional variations in unemployment across India. It also highlighted a significant increase in unemployment during the COVID-19 period. Through data cleaning, exploratory data analysis, and visualization, the project helped identify unemployment patterns and examine changes in employment indicators over time.

## Project Structure

```text
DataScience-Task2-UnemploymentAnalysis/
│
├── README.md
└── unemplyoment_in_India.ipynb
```

## Internship

**Oasis Infobyte – Data Science Internship**

**Task 2:** Unemployment Analysis with Python

## 👩‍💻 Internship
**Oasis Infobyte Data Science Internship – Task 2**
