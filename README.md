# Real-Estate-analyze


Project Overview

This project is built with Python and focuses on analyzing the real estate market in Azerbaijan using machine learning regression methods. It explores housing data scraped from Binaz.az—the largest real estate platform in the country—and provides predictive insights into property pricing.


Purpose & Usefulness

The core goal of this project is to predict reasonable property prices based on several key features such as:

area_m2
floor
room_count
district
repair_status
This tool can be valuable for:

Real estate companies seeking to estimate property prices by region and housing conditions.
Buyers and sellers who want to verify if their price expectations are aligned with market data.
Mortgage analysts who need accurate housing valuations for loan decisions.

Technologies & Methods Used

Web Scraping: Data collected via BeautifulSoup from Binaz.az.
Data Cleaning & Preparation: Included null handling, standardization, and transformation.
Exploratory Data Analysis (EDA): Visualizations, descriptive statistics, and outlier detection.
Machine Learning Models:
Linear Regression
Random Forest Regressor
XGBoost Regressor (optional, install with pip install xgboost)
Performance Metrics: RMSE and R² Score for model evaluation.


Key Steps in the Workflow

Data Scraping from website listings.
Data Preprocessing – formatting, cleaning, feature engineering.
Exploratory Analysis – charts, distributions, correlation heatmaps.
Outlier Detection – via IQR method.
Model Training – using multiple regression algorithms.
Model Evaluation – using RMSE and R² metrics.
