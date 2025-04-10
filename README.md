# 🌍 Worldwide Unemployment Rates

An insightful time series data science project analyzing global unemployment trends from 1991 to 2021 and forecasting to 2026.

---

## 🧭 Overview

In today's world, unemployment has become a significant global concern due to various economic causes. Inspired by the idea of analyzing a country's unemployment rate over the past 31 years, the project organizers established **"Worldwide Unemployment Rates"**.

This data science project was developed for the **DE242 Introduction to Data Science** course at Srinakharinwirot University. It focuses on **time series analysis** using the **ARIMA model**, visualizations, and evaluation metrics.

---

## 📁 Dataset

- 📌 Source: Kaggle
- 🧮 Rows: 235 → Refined to 195 countries
- 📅 Columns: 33 → Expanded to 34 (including Country, Continent, Code, and years 1991–2021)
- 🧼 Cleaning: Redundant values removed and countries standardized

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas, NumPy, Matplotlib, Seaborn
- Plotly (Choropleth Maps)
- ARIMA (AutoRegressive Integrated Moving Average)
- Evaluation Metrics: MAD, MSE, RMSE, MAPE

---

## 📊 Key Visualizations

- Choropleth maps (before and after prediction)
- Histogram of Unemployment Distribution
- Time series graphs by country
- Forecast trends (2022–2026)

---

## 🔍 Model Performance

| Metric | Min Country | Min Value | Max Country | Max Value |
|--------|-------------|-----------|-------------|-----------|
| MAD    | Uganda      | 0.00000   | Bosnia and Herzegovina | 3.86600 |
| MSE    | Bahrain     | 0.00012   | North Macedonia         | 107.78655 |
| RMSE   | Bahrain     | 0.01074   | North Macedonia         | 10.38203 |
| MAPE   | Gabon       | 0.00217   | Cambodia                | 3.31845  |

> ⏱️ Average Model Execution Time: ~7 minutes

---

## 🔮 Forecasting Future Trends

Using ARIMA, we predicted unemployment rates from **2022 to 2026**. While the model provides insights, external socio-economic uncertainties must be considered when interpreting the forecast.

---

## ✅ Conclusion

This project:

- Demonstrated ARIMA-based time series forecasting
- Visualized historical and future unemployment rates
- Emphasized the global patterns and anomalies in unemployment
- Provided a base for strategic thinking on unemployment challenges

The project enhanced our skills in **data wrangling**, **forecast modeling**, and **interactive data visualization**, setting the foundation for future research into global economic indicators.

> _"Understanding the past helps us better predict and prepare for the future."_ 🌐
