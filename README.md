# Delhi Air Quality Analysis Dashboard
Analyzed air quality data using Power BI to uncover AQI trends, pollutant levels, and seasonal patterns.

# Dataset Overview 
Source: https://www.kaggle.com/datasets/kunshbhatia/delhi-air-quality-dataset/versions/1/data

This dataset contains daily records of air pollutant concentrations collected over time, including PM2.5, PM10, NO₂, SO₂, CO, and Ozone. It also logs the Air Quality Index (AQI), along with date (day, month, year) also includes number of holidays and weekday representation. 

The data is based on the amount of particulate matter in the air, which is measured in micrograms per cubic meter (µg/m³). The particulate matter includes dust, smoke, and other small particles.

# Project Overview
This project focuses on analyzing air quality data from 2021 to 2024 to understand pollution trends, key pollutant behaviour, and time-based patterns. The analysis highlights critical issues such as consistently unhealthy AQI levels, high particulate matter concentrations (PM10 and PM2.5), and seasonal spikes in pollution.

# Tools Used
- Power BI – Data visualization and interactive dashboard creation
- DAX (Data Analysis Expressions) – Calculated measures and KPIs
- Power Query – Data cleaning and transformation

# Data Insights
### 1. Overall Air Quality Insights
- The average AQI across the entire period is 202.21, which falls under the Unhealthy category, indicating consistently poor air quality conditions.
- AQI exceeded acceptable limits on 898 days, showing chronic pollution exposure.
- From 2021 to 2024, 26.28% of days fall in the ‘Unhealthy’ AQI category, confirming long-term air quality worsened.

<img width="1878" height="934" alt="Image" src="https://github.com/user-attachments/assets/1f6cc028-8611-4b78-84c1-bcd50fcebff9" />

### 2. Pollutant Insights (PM10 & PM2.5)
- The average PM10 level is 218.22, while average PM2.5 is 90.77, both significantly above recommended health limits.
- PM10 levels peaked in 2024 at 229.1, indicating worsening dust and coarse particulate pollution in recent years.
- PM2.5 levels were highest in 2020 at 120, suggesting strong fine-particle pollution, likely from combustion sources.
- Scatter plot analysis shows a clear positive correlation:
     AQI increases sharply when PM10 and PM2.5 increase, confirming both pollutants as major contributors to poor air quality.

<img width="1883" height="933" alt="Image" src="https://github.com/user-attachments/assets/c46b6d18-1b98-490c-b67c-e9bdbf700e56" />

### 4. Time-Based Insights (Holiday vs Weekday)
- Average AQI was highest in 2021 and shows a gradual decline up to 2023, indicating slow improvement but still remaining well above safe limits.
- November shows the highest monthly AQI with an average of 342.13, making it the most polluted month—likely due to winter inversion and lower wind speeds.
- Average AQI on holidays is 202.31, slightly higher than weekdays (202.19), indicating marginally higher pollution levels on weekends.

<img width="1666" height="829" alt="Image" src="https://github.com/user-attachments/assets/9d763af4-6e3e-4cca-8e99-5d37430387cb" />
