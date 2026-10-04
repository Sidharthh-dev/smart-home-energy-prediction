# Smart Home Energy Prediction

Data exploration of a smart home electricity dataset, with the aim of predicting electricity price per kWh using Python and machine learning.

## About

This project started as a four-member team project during my AICTE internship at Inspire Softech Solutions, Chennai (May 2026). This repository holds my data exploration notebook. The modelling stage is in progress.

## Dataset

- 1,752,000 rows and 16 columns of smart home device readings from 10 homes (home_id 1 to 10)
- Columns: home_id, timestamp, device_id, device_type, room, status, power_watt, user_present, activity, indoor_temp, outdoor_temp, humidity, light_level, day_of_week, hour_of_day, price_kWh
- No missing values
- The CSV file is not included in this repository because of its size
- Source: Provided during the internship training at Inspire Softech Solutions

## What is done so far

- Loaded the dataset and checked its structure (info, describe, null check)
- Plotted histograms of all numeric features
- Built a correlation heatmap to see how features relate to price_kWh

## Next steps

- Prepare the data and split it into training and test sets
- Train a Random Forest Regressor
- Evaluate it with MAE and R2 and plot feature importance

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## Files

- 01_data_exploration.ipynb: data loading, summary statistics, histograms and correlation heatmap
