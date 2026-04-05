# Unemployment Analysis with Python: COVID-19 Impact Study

## 📌 Project Overview
This project focuses on analyzing the unemployment rate in India during the year 2020. The primary goal is to visualize and understand how the global COVID-19 pandemic and subsequent lockdowns affected the labor market across different regions.

## 📊 Key Objectives
* **Data Cleaning:** Handling missing values and formatting date-time objects for time-series analysis.
* **Exploratory Data Analysis (EDA):** Identifying peaks, troughs, and regional variations.
* **Impact Analysis:** Specifically pinpointing the surge in unemployment during the lockdown period (March–June 2020).
* **Policy Insights:** Interpreting data trends to suggest economic resilience strategies.

## 🛠️ Technologies Used
* **Python** (Core Analysis)
* **Pandas** (Data Manipulation)
* **Matplotlib & Seaborn** (Data Visualization)
* **Jupyter Notebook** (Development Environment)

## 📂 Dataset Details
The analysis uses the `Unemployment_Rate_upto_11_2020.csv` dataset, which contains:
* **Region:** The specific state/area in India.
* **Date:** The timeline of data collection.
* **Estimated Unemployment Rate (%):** The percentage of the labor force without work.
* **Estimated Employed:** Total number of people currently employed.
* **Estimated Labour Participation Rate (%):** The percentage of the population active in the labor market.

## 🚀 Analysis Workflow

### 1. Data Preprocessing
Ensured all column names were stripped of hidden spaces and converted the `Date` column into a standard `datetime` format to allow for accurate chronological plotting.

### 2. Visualization & Trends
Created line charts and bar plots to visualize:
* The sharp spike in unemployment starting in **April 2020**.
* Comparison of average unemployment rates across different Indian states.

### 3. COVID-19 Impact
By adding a timeline marker at March 2020, the project visually demonstrates the immediate correlation between the pandemic outbreak and the economic downturn.

## 📈 Visualizations
![Unemployment Trend](unemployment_plot.png) 

## 💡 Key Insights
* **The Lockdown Peak:** Unemployment peaked dramatically in April and May 2020, coinciding with the strictest lockdown phases.
* **Regional Resilience:** Certain states showed higher volatility, indicating a need for more localized economic support structures.
* **Recovery Observation:** A gradual decline in rates was observed after July 2020 as economic activities slowly resumed.

## 🏁 How to Run
1. Clone the repository.
2. Ensure you have `pandas`, `matplotlib`, and `seaborn` installed.
3. Run the Jupyter Notebook `Unemployment_Analysis.ipynb`.
