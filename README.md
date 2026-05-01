# 🌦 Weather Analytics & Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Project Overview
This project analyzes historical weather data to identify trends, detect anomalies, and predict future temperature using machine learning and time-series models.

## 🎯 Problem Statement
Can we analyze past weather patterns to predict future climate trends and detect extreme weather conditions?

## 📊 Dataset

This project uses weather datasets containing temperature, rainfall, and climate features.

### 📁 Data Sources
- **India Daily Weather Data (2000–2024)**  
  [View Dataset](https://www.kaggle.com/datasets/developerghost/climate-in-india-daily-weather-data-2000-2024)
   Historical daily weather observations across India.

- **Indian Climate Dataset (2024–2025)**  
  [View Dataset](https://www.kaggle.com/datasets/ankushrawade/indian-climate-dataset-20242025)
   Recent climate trends including temperature and rainfall patterns.

### 📑 Features in Dataset
- Temperature (min, max, avg)
- Rainfall
- Humidity
- Wind Speed
- Air Quality Index (AQI)
- Pressure
- Cloud Cover

## 💼 Business Use Case

This project helps in:
- Understanding climate change patterns  
- Predicting future weather conditions  
- Supporting agriculture and planning decisions  
- Identifying extreme weather risks  

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- ARIMA  

## ⚙️ Workflow
Data Cleaning → EDA → Trend Analysis → Anomaly Detection → Prediction → Visualization

## 📈 Key Features
- Temperature trend analysis  
- Rainfall anomaly detection  
- Extreme weather identification  
- Future prediction  

## 📷 Visualizations & Insights

### 🌡 Temperature Forecast

<p align="center">
  <img src="Temperature Forecast.png" width="700"/>
</p>

**Insight:** Temperature shows periodic fluctuations with a relatively stable forecast trend.

---

### 🌧 Rainfall Anomaly Detection

<p align="center">
  <img src="Rainfall Anomaly Detection.png" width="700"/>
</p>

**Insight:** Certain years exhibit significant deviations from average rainfall, indicating potential climate anomalies.

---

### 🏙 Climate Segmentation of Cities

<p align="center">
  <img src="Climate Segmentation of Cities.png" width="700"/>
</p>

**Insight:** Cities cluster differently based on temperature and rainfall, highlighting distinct regional climate patterns.

---

### ⚖️ Extreme vs Normal Weather Distribution

<p align="center">
  <img src="Extreme vs Normal Weather Distribution.png" width="500"/>
</p>

**Insight:** Majority of weather conditions remain normal, but a notable portion reflects extreme events.

---

### 🔗 Correlation Matrix

<p align="center">
  <img src="Correlation Matrix.png" width="700"/>
</p>

**Insight:** Strong positive correlation exists between temperature variables, while other factors show weaker relationships.

---

### 📈 Future Trend of Extreme Weather

<p align="center">
  <img src="Future Trend of Extreme Weather.png" width="700"/>
</p>

**Insight:** Extreme weather events show a slight increasing trend over time, indicating potential climate risk growth.

## 📌 Key Insights

- Temperature exhibits periodic fluctuations with stable future predictions  
- Rainfall anomalies highlight irregular climate patterns in certain years  
- Strong correlations exist among temperature-related variables  
- Climate segmentation reveals distinct regional weather characteristics  
- Extreme weather events show a gradual increasing trend over time

## ⚠️ Limitations
- Limited dataset size  
- Accuracy depends on historical data  

## 🔮 Future Improvements
- Real-time data integration  
- Advanced models (LSTM)  
- Dashboard deployment  

## 🤖 Models Used

- Time Series Forecasting (ARIMA)
- Statistical Analysis
- Correlation Analysis

## 📏 Model Evaluation

- Forecasting approach: ARIMA  
- Model performance evaluated using trend comparison  
- Predictions show stable future patterns with minor fluctuations  

## 🚀 Conclusion

This project demonstrates how data analysis and machine learning can be used to understand climate patterns, detect anomalies, and support data-driven decision-making.
