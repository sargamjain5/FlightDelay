# ✈️ Flight Delay Analysis & Prediction

This project analyzes airline flight delay data and builds models to predict both:
- Whether a flight will be delayed (classification).
- How many minutes a flight will be delayed (regression).

It uses EDA, data cleaning, and machine learning on features like carrier delay counts, weather delays, NAS delays, late aircraft delays, and more.

---

## 📊 Features

✅ Exploratory Data Analysis (EDA) with visualizations:
- Histograms, boxplots, heatmaps of delay causes.
- Correlation heatmaps.

✅ Classification model:
- Predicts if a flight will be delayed (>15 minutes) or on time.
- RandomForestClassifier with performance metrics and confusion matrix.

✅ Regression model:
- Predicts exact arrival delay in minutes.
- LinearRegression with error metrics and actual vs. predicted plots.

✅ Prediction on new data:
- Generate delay predictions for custom flight scenarios.

✅ Cleaned dataset:
- Missing values handled.
- Outliers filtered.

---

## 📁 Dataset

Uses cleaned flight delay data (`CleanedData.csv`) containing columns like:
- `carrier_ct`, `weather_ct`, `nas_ct`, `late_aircraft_ct`
- `carrier_delay`, `weather_delay`, `nas_delay`, `late_aircraft_delay`
- `arr_cancelled`, `arr_diverted`, `month`
- `arr_delay` (target for regression)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sargamjain5/FlightDelay.git
   cd FlightDelay
