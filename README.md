# 🚴 Bike Rental Analysis 🚴

## Introduction

This repository contains a comprehensive analysis of the bike rental dataset from the Capital Bikeshare system. The dataset captures both hourly and daily counts of bike rentals between the years 2011 and 2012, along with various environmental and seasonal information.

## Objective

The primary goal of this analysis is to understand the factors affecting bike rentals and derive insights that can potentially help in improving the bike rental service and predicting future rentals.

## Datasets

There are two primary datasets used:

1. **Daily Data (`day.csv`)**:
   - Granularity: Daily
   - Features: Date, season, year, month, holiday, weekday, working day, weather situation, temperature, humidity, windspeed, casual rentals, registered rentals, total count.
   
2. **Hourly Data (`hour.csv`)**:
   - Granularity: Hourly
   - Features: Date, hour, season, year, month, holiday, weekday, working day, weather situation, temperature, humidity, windspeed, casual rentals, registered rentals, total count.

## Project Workflow

1. **Initial Data Exploration**: 
   - A deep dive into the dataset to understand its basic properties, distribution of variables, and potential data quality issues.
   
2. **Visualization**: 
   - Extensive visualizations were conducted to uncover patterns, relationships, and trends in the data.
   
3. **Data Cleaning**: 
   - Outliers and inconsistencies were identified and handled to ensure the reliability of the analysis.
   
4. **Feature Engineering**: 
   - New features were derived to enhance the informational content of the dataset, such as determining rush hours and day types.

## Key Insights

- There is a clear upward trend in bike rentals over the years, suggesting growing popularity.
- Bike rentals exhibit seasonality, with peaks during certain times of the day, particularly during morning and evening rush hours.
- Environmental factors like temperature, humidity, and windspeed significantly influence rental patterns.

## Tools & Technologies

- **Python**: The primary language used for analysis.
- **Pandas**: For data wrangling and analysis.
- **Matplotlib & Seaborn**: Visualization libraries used to derive insights from the data.

