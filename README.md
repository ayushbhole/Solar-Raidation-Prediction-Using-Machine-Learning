# ☀️ Solar Radiation Prediction: A Machine Learning Approach  

---

## 🎯 Objective  
---
The main objective of this project is to **develop and evaluate robust machine learning models** for accurate daily **solar radiation prediction**.  
The goal is to identify a high-performing model — such as a **Stacked Ensemble Model** — that minimizes prediction errors.  

---

## 🌍 About Solar Radiation Prediction  
---
Solar radiation is a critical meteorological parameter with wide applications in **agriculture, climate studies, and renewable energy management**.  

---

## 📝 Problem Statement  
---
Predicting solar radiation is challenging due to the **dynamic nature of the atmosphere**.  
This project builds a **reliable predictive framework** using **advanced ensemble learning techniques**.  

---

## 📊 Dataset Overview  
---
The dataset consists of **historical meteorological time-series data** sourced from **NASA POWER (2023–2024)**.  

### Key Variables  

| Features | Description |  
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

**Dataset link:** [Solar Radiation Data](<Insert your dataset link here>)  

---

## 🛠️ Methodology  
---
1. Data Collection & Preprocessing  
2. Feature Engineering  
3. Model Selection & AutoML  
4. Training & Hyperparameter Tuning  
5. Model Evaluation  
6. Visualization  

---

## 💡 Key Concepts Used  
---
* Time Series Analysis  
* Regression Models  
* Ensemble & Stacked Modeling  
* AutoML for Feature Selection  
* Model Evaluation (R², MAE, MSE, RMSE)  

---

## 📂 Files in this Repository  
---
| File Type | Description |  
| :--- | :--- |  
| **Jupyter Notebook** | `Solar_Radiation_Prediction.ipynb` |  
| **PDF Report** | `Solar_Radiation_Analysis_Report.pdf` |  
| **Dataset** | `Solar_Radiation_Data.csv` |  

---

💻 **Compiled by Ayush**  
