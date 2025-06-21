# Beverage-Demand-Forecasting-Inventory-Recommendation-System

🍹 Beverage Demand Forecasting & Inventory Recommendation System
This project aims to forecast beverage consumption and recommend optimal inventory (par) levels for a growing hotel chain with multiple bars. By analyzing historical sales data, the system helps reduce stockouts and overstocking using advanced time series models and machine learning techniques.

📌 Project Objectives
Forecast item-level beverage demand.

Recommend inventory (par) levels based on predicted consumption.

Reduce stockouts, over-purchasing, and waste.

Deploy a user-friendly web app using Streamlit.

🧠 Techniques Used
Time Series Forecasting (LightGBM, SARIMA, Exponential Smoothing)

Feature Engineering

Outlier Detection & Handling

Skewness Correction

Model Evaluation (MSE, MAE, R² Score)

Inventory Recommendation Logic

Streamlit Deployment

📊 Dataset Overview
Source: Real-world beverage consumption data (internal simulation).

Columns: Date, Outlet Name, Item Name, Consumed (ml), etc.

Granularity: Daily item-level consumption.

Size: ~18,000 records.

🔧 Tech Stack
Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, lightgbm, statsmodels, scikit-learn, streamlit, joblib

Deployment: Streamlit app hosted on AWS EC2

Tracking: MLflow (for experiment tracking)

🚀 Features of the Web App
📈 Forecast future beverage demand for any outlet/item

🧮 Recommend optimal inventory (par) levels based on forecast

📉 Visualize trends and seasonal patterns

🔎 User input selection for outlet, item, and forecast days
