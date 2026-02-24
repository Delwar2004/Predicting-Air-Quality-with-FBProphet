# 🌍 Predicting-Air-Quality-with-FBProphet

This project demonstrates a complete time-series forecasting pipeline to predict Air Quality (Relative Humidity) using historical sensor data. The model is built using the **Facebook Prophet** library to capture trends and seasonal patterns.

## 🚀 Project Overview
- **Goal:** Predict hourly Air Quality trends (Relative Humidity) using time-series forecasting.
- **Dataset:** Air Quality UCI Dataset (responses of a gas multi-sensor device).
- **Model:** FB Prophet (Additive Model).

## 🛠️ Data Cleaning & Preparation
To ensure high model accuracy, the following steps were performed:
- **Trimming:** Identified the boundary of valid data (index 9356) and removed trailing null rows.
- **Missing Value Handling:** Replaced placeholder values (-200) with `NaN` and applied Mean Imputation.
- **Feature Engineering:** Combined 'Date' and 'Time' columns into a single unified `ds` (datestamp) column required by Prophet.

## 📊 Insights from Visualization
The model analyzed patterns across different time scales:
- **Trend:** Observed the overall movement of air quality over the months.
- **Weekly Patterns:** Identified pollution cycles during weekdays vs weekends.
- **Daily Cycles:** Analyzed peak hours where air quality fluctuates significantly.



## 🏁 Installation & Usage
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone:
   [[https://github.com/Delwar2004/Predicting-Air-Quality-with-FBProphet.git]](https://github.com/Delwar2004/Predicting-Air-Quality-with-FBProphet)
Install necessary libraries:

Bash
pip install pandas numpy matplotlib prophet
Run the Notebook:
Open Air_Quality_Index_Prediction.ipynb in Jupyter Notebook or VS Code and run all cells.

📂 Technologies Used
Python (Pandas, NumPy, Matplotlib)

FB Prophet (Forecasting Engine)

<p align="center">
  <i>Developed by <b>Delwar</b></i>
</p>
