# ☀️ Solar Radiation Prediction: A Machine Learning Approach  

<p align="center">
  <img src="Solar%20Radiation%20Prediction.jpeg" alt="Solar Radiation Prediction" width="600"/>
</p>

---
## 🎯 Objective  
The main objective of this project is to **develop and evaluate robust machine learning models** for accurate daily **solar radiation prediction**.  
This study focuses on identifying a **high-performing model** that minimizes prediction errors and improves forecasting reliability.  

To achieve this, both **individual machine learning models** and a **Stacked Ensemble Model** were implemented.  
Additionally, **AutoML techniques** were applied for **automatic feature selection and hyperparameter tuning**.  

---

## 🌍 About Solar Radiation Prediction  
Solar radiation is a critical meteorological parameter with applications in:  

- 🌱 Agriculture – crop yield estimation and irrigation planning  
- 🌍 Climate studies – understanding energy balance and atmospheric changes  
- ⚡ Renewable energy systems – optimizing photovoltaic (PV) panels, thermal plants, and smart grids  

Accurate prediction of solar radiation is crucial for **maximizing energy harvest, improving grid stability, and enabling smarter energy planning**.  

---

## 📝 Problem Statement  
Predicting solar radiation is difficult due to the **highly dynamic nature of the atmosphere**, which is influenced by:  

- Cloud cover ☁️  
- Humidity 💧  
- Temperature 🌡️  
- Seasonal patterns 📅  

Traditional single-model approaches often fail to capture this complexity.  
This project aims to build a **reliable predictive framework** using **ensemble learning and AutoML** for robust and accurate forecasting.  

---

## 📊 Dataset Overview  
The dataset consists of **13,000+ historical meteorological time-series records** sourced from **NASA POWER (2023–2024)**.  
The target variable is **ALLSKY_SFC_SW_DWN (Solar Radiation at the surface in W/m²)**.  

### Key Features  

| Feature | Description |  
| :--- | :--- |  
| **ALLSKY_SFC_SW_DWN** | Solar radiation at the surface (Target Variable) |  
| **Temperature** | Air temperature (°C) |  
| **Relative_Humidity** | Relative humidity (%) |  
| **Surface_Pressure** | Atmospheric surface pressure (kPa) |  
| **Wind_Speed** | Wind speed at 2 meters (m/s) |  
| **hour** | Hour of the day (0–23) |  
| **day_of_week** | Day of the week (0 = Monday … 6 = Sunday) |  
| **month** | Month of the year (1–12) |  
| **week_of_year** | Week number of the year (1–52) |  
| **is_weekend** | Binary indicator (1 = weekend, 0 = weekday) |  
| **day_of_year** | Day number of the year (1–365) |  
| **Wind_Power** | Derived wind power feature from wind speed |  
| **prev_hour_radiation** | Lag feature: radiation in the previous hour |  
| **radiation_rolling_3** | Rolling average of radiation over the past 3 hours |  

📂 **Dataset link:** [Solar Radiation Data](https://github.com/ayushbhole/Solar-Raidation-Prediction-Using-Machine-Learning/blob/main/cleaned_solar_dataset.csv)  

---

## 🛠️ Methodology  
1. **Data Collection & Preprocessing** – NASA POWER data, missing value handling, outlier removal, scaling.  
2. **Feature Engineering** – Lag variables, rolling averages, and temporal features (hour, day, month, seasonality).  
3. **Model Selection & AutoML** – Used tree-based models (XGBoost, Random Forest, LightGBM), Neural Networks, and **AutoML for feature selection & hyperparameter tuning**.  
4. **Model Building** – Trained individual models and a **Stacked Ensemble Model** for better performance.  
5. **Evaluation** – Metrics: R², MAE, MSE, RMSE with **cross-validation**.  
6. **Visualization** – Plots of actual vs. predicted radiation, feature importance charts.  

---

## 💡 Key Concepts Used  
- Time Series Feature Engineering (lag features, rolling averages)  
- Machine Learning Regression Models (XGBoost, Random Forest, LightGBM, Neural Networks)  
- **AutoML for automatic feature selection & tuning**  
- Ensemble & Stacked Modeling  
- Model Evaluation with R², MAE, MSE, RMSE  
- Data Visualization  

---

## 📂 Files in this Repository  

| File Type | Description |  
| :--- | :--- |  
| **Jupyter Notebook** | `Solar_Radiation_Prediction.ipynb` – Full implementation & analysis |  
| **PDF Report** | `Black_Book_Report.pdf` – Detailed research paper/report |  
| **Dataset** | `cleaned_solar_dataset.csv` – Processed dataset used in the project |  

---

💻 **Compiled by Ayush**  
