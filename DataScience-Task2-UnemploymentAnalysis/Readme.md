# Unemployment Analysis with Python

## Oasis Infobyte Data Science Internship — Task 2

This project performs an exploratory data analysis (EDA) of unemployment trends in India using Python. The analysis focuses on regional and temporal unemployment patterns and examines changes around the COVID-19 pandemic period.

---

## Objective

The main objective of this project is to analyze unemployment data in India and identify:

- Regional differences in unemployment rates
- Monthly and time-based unemployment trends
- States/regions with higher average unemployment rates
- Relationships between unemployment, employment, and labour participation
- Changes in unemployment before and after the COVID-19 period
- Differences between rural and urban areas

---

## Technologies Used

- **Python**
- **Pandas** – data cleaning and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Jupyter Notebook** – analysis and documentation

---

## Dataset

The project uses the **Unemployment in India** dataset available through Kaggle.

**Dataset Source:**  
https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india

The dataset contains unemployment-related information for Indian states and union territories, including:

- Region / State
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area type (Rural / Urban)

The cleaned dataset used in the analysis contains approximately **740 records**, covering **28 states/union territories** from **May 2019 to June 2020**.

---

## Data Preparation

The following data preparation steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected the dataset shape and structure.
3. Checked for missing values.
4. Removed incomplete records.
5. Standardized column names and text values.
6. Converted the date column into a proper datetime format.
7. Extracted year, month, and month name from the date.
8. Renamed important variables for easier analysis.
9. Prepared the data for regional and time-series analysis.

---

## Exploratory Data Analysis

### 1. Region-wise Average Unemployment

The average unemployment rate was calculated for different states and union territories to identify regional differences.

### 2. Monthly Unemployment Trends

Monthly unemployment rates were analyzed to understand how unemployment changed over the study period.

### 3. State-wise Time-Series Analysis

A time-series line chart was created for selected major states, including:

- Maharashtra
- Tamil Nadu
- Uttar Pradesh
- Delhi
- Karnataka

This visualization helps compare unemployment trends across different regions over time.

### 4. Top 10 States with Highest Average Unemployment

A bar chart was created to identify the ten states/union territories with the highest average unemployment rates during the analyzed period.

### 5. Correlation Heatmap

A correlation heatmap was created to examine relationships among:

- Unemployment Rate
- Employment Rate Proxy
- Labour Participation Rate

> **Note:** The original dataset provides estimated employment as an absolute number rather than an employment-to-population percentage. Therefore, the notebook uses `100 - Unemployment Rate` as an employment-rate proxy for the correlation visualization.

### 6. COVID-19 Period Comparison

The analysis compares unemployment levels before and during the COVID-19 period to examine changes in unemployment rates.

### 7. Rural vs Urban Analysis

Where applicable, unemployment patterns were compared between rural and urban areas to identify differences in unemployment levels.

---

## Key Visualizations

The notebook includes:

- 📈 Regional average unemployment analysis
- 📈 Monthly unemployment trend
- 📉 State-wise time-series line chart
- 📊 Top 10 states by average unemployment
- 🔥 Correlation heatmap
- 📊 Pre-COVID vs post-COVID comparison
- 📊 State-wise COVID-period impact
- 📊 Rural vs urban comparison

---

## Key Observations

The analysis is designed to identify:

- Differences in unemployment rates across Indian states and union territories
- Changes in unemployment over time
- Higher and lower unemployment regions during the study period
- Changes in unemployment associated with the COVID-19 period
- Differences between rural and urban unemployment patterns
- Relationships between unemployment and labour participation indicators

Detailed observations and interpretations are provided within the Jupyter Notebook after the corresponding visualizations.

---

👩‍💻 Author

Mina Fatima

Data Science Internship Project
Oasis Infobyte
