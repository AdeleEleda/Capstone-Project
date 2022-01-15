# Capstone-Project
# Time Series Modeling Energy Demand
Brainstation Data Science Capstone Project
Adele DuBay
Sept 2021

### **Data Cleaning**\
see "capstone_data_cleaning.ipynb"

In this notebook we will clean and combine the raw data in CSVs collected from the publicly available Hourly Load Data Archives. These data sets contain the hourly energy load, measured in MW, for the eight regions that make up the electric grid monitored by the Electric Reliability Council of Texas and spans from 2008-2019. The goal of cleaning and compiling the data into one CSV is to build statistical models in order to forecast future energy demand.


### **Exploratory Data Analysis**\
File too large, may attach at later date. 


### **Modeling**\
see "capstone_early_models-Copy1.ipynb"

In this notebook we'll do some exploratory data analysis on a cleaned dataset that originated from the Hourly Load Data from the Electric Reliability Council of Texas (ERCOT) Archives website. This data contains information on the hourly energy load, measured in MW, from 2008-2019 for the eight regions that make up the electric grid monitored by the ERCOT. The grid monitored by ERCOT covers almost all of Texas.


### **Advanced Models**\
see "capstone_advanced_models-Copy1.ipynb"

This notebook contains several attempts at creating Simple Neural Networks, Recurrent Neural Networks, and Long Short Term Memory (LSTM) networks for my Forecasting Energy Demand Capstone. Each needs further revisiting.


### Reccomendations and Next Steps
- Find and incorporate additional data such as temperature, weather (cloudy/sunny/windy), and population growth, in order to improve model performance and gain further insights.
- Hone and optimize current in-progress models: KNN, optimize RNN, LSTM.
- Explore more models such as Vector Autoregressive to include more features. Then observe their performance, similarities, and differences.
