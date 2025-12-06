# Airline-Passenger-Demand-Forecasting
Forecasts monthly international airline passenger demand using historical data. Includes data cleaning, EDA, feature engineering, and modeling with SARIMAX and Random Forest. Generates 12–24 month forecasts with visualizations and a Power BI dashboard for aviation planning.

Forecasting monthly international airline passenger demand using time-series techniques, machine learning models, and data visualizations.

---

##  Project Overview
This project predicts monthly international airline passenger demand using historical U.S. aviation data (1990–2020). The objective is to build accurate 12–24 month forecasts that help airlines, airports, and tourism authorities optimize scheduling, capacity planning, and operational decisions.

The workflow includes data preprocessing, exploratory analysis, feature engineering, modeling (SARIMAX and Random Forest), evaluation, and final forecasting with visual insights.

---

## Dataset
Source: U.S. Bureau of Transportation Statistics / Kaggle  
Includes:
- Monthly passenger counts  
- Airport codes (IATA)  
- Scheduled & charter passengers  
- Carrier and region information  

Main variable used: **Total Monthly Passengers**

---

## Technologies Used
- Python, Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- statsmodels (SARIMAX)  
- scikit-learn (Random Forest)  
- Power BI  
- Git/GitHub  

---

## Project Workflow
1. **Data Cleaning** – Parse dates, handle missing values, monthly resampling  
2. **EDA** – Trend, seasonality, decomposition, correlations  
3. **Feature Engineering** – Lag features, rolling averages, month & year  
4. **Modeling**  
   - SARIMAX  
   - Random Forest Regression  
5. **Evaluation** – MAE, RMSE, MAPE  
6. **Forecasting** – 12–24 month demand prediction  
7. **Visualization** – Forecast plots & dashboards  

---

## Key Outputs
- Cleaned and processed dataset  
- Forecasted passenger demand charts  
- Model performance comparison  
- Power BI dashboard  
- Exportable prediction files  

---

## Repository Structure
project/
│
├── data/
├── notebooks/
├── src/
├── visuals/
├── documentation/
└── README.md

---

## License
This project is licensed under the **MIT License**.
