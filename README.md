# 🚲 Bike Rentals Analysis

Welcome to my data science project using the UCI Bike Sharing Dataset!

In this project, I analyze daily bike rental data to understand what factors most strongly influence bike usage and to evaluate forecasting and regression models that can support real‑world transit planning and operational decision‑making.

---

## 📊 Project Overview

This project walks through a complete data analytics and machine learning workflow:

- Data loading and exploration  
- Data cleaning and validation  
- Exploratory data analysis (EDA)  
- Time‑series visualization and trend analysis  
- Forecasting using baseline and smoothing methods  
- Regression modeling to predict daily bike rental demand  
- Model evaluation and interpretation  

**Goal:**  
Identify the key drivers of daily bike rentals and develop short‑term forecasting insights that could help transportation planners anticipate demand and allocate resources more effectively.

---

## 🧠 Skills Demonstrated

- Data analysis and cleaning with **Pandas**  
- Numerical computing with **NumPy**  
- Data visualization with **Matplotlib** and **Seaborn**  
- Time‑series analysis with **statsmodels**  
- Machine learning with **scikit‑learn**  
- Forecast evaluation (MAPE, MAE, MSE, RMSE, R²)  
- Linear regression and feature selection techniques  
- Model diagnostics and residual analysis  
- Reproducible, GitHub‑ready project organization  

---

## 📁 Dataset

The dataset used in this project comes from the **UCI Bike Sharing Dataset**.

**Bike Sharing – Daily Data (`day.csv`)**

- Each row represents **one day** of bike rental activity  
- Target variable:
  - `cnt`: Total number of bike rentals per day  

### Key Features Include:

- `season`  
- `yr` (2011 or 2012)  
- `mnth`  
- `weekday`  
- `workingday`  
- `holiday`  
- `weathersit` (weather condition category)  
- `temp` (normalized temperature)  
- `atemp` (normalized “feels‑like” temperature)  
- `hum` (humidity)  
- `windspeed`  
- `casual` and `registered` user counts  

> The dataset is read locally from `day.csv` and is not downloaded automatically by the code.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/bike-rentals-analysis.git
cd bike-rentals-analysis
``
