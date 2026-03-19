# 🏭 Air Quality Dashboard

A **Streamlit-powered interactive dashboard** for visualizing and analyzing air pollution (AQI and major pollutants) in Indian cities over time.

## 📊 Overview

This dashboard allows users to:

- Explore **AQI (Air Quality Index)** trends by city and by year
- Analyze AQI distribution across **AQI Buckets**
- Monitor **pollutant levels** such as PM2.5, PM10, NO2, and more over time
- Gain insights into **air quality patterns** and seasonal variations across cities

## 🚀 Features

✅ AQI Visualization by:
- City
- Year
- AQI Bucket

✅ Pollutants Over Time:
- Track pollutant levels like PM2.5, PM10, NO2, CO, etc.

✅ Streamlit UI:
- Sidebar controls for dynamic filtering
- Matplotlib & Seaborn plots integrated with Streamlit
- Interactive dropdowns and multiselect options

---

## 🧾 Dataset

- Source: `Data/city_day.csv`
- Columns used: `Date`, `City`, `AQI`, `AQI_Bucket`, and multiple pollutants like `PM2.5`, `PM10`, `NO2`, `CO`, etc.

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Streamlit** for interactive web UI
- **Pandas** for data processing
- **Seaborn** & **Matplotlib** for data visualization

