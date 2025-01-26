# CIDM-6305
Business Intelligence and Decision Systems


# Business Intelligence and Machine Learning Project for Predicting Vehicle Selling Prices
## Overview
This project focuses on leveraging advanced analytics and machine learning techniques to predict vehicle selling prices for All American Motors Corp. (AAMC). By analyzing historical sales data, market trends, and consumer behaviors, the project aims to optimize sales forecasting, enhance inventory management, and improve revenue generation.

# Project Phases
# Phase 1: Data Collection and Cleaning
Data Source: Historical vehicle sales data from Kaggle's "Vehicle Sales and Market Trends Dataset."
Dataset Overview: Includes 16 attributes and ~100,000 records detailing sales transactions, vehicle conditions, and market factors.
Key Steps:
Data preprocessing (handling missing values, detecting outliers, normalization).
Feature identification using correlation analysis, PCA, and lasso regression.

# Phase 2: Model Development
Objective: Predict vehicle selling prices based on features such as year, make, model, transmission, and condition.
Modeling:
Trained using AutoML in Azure.
Regression models considered: Linear Regression, LightGBM, Decision Tree, ElasticNet, and Voting Ensemble.
Best Model: Voting Ensemble, achieving a normalized root mean squared error (RMSE) of 0.01698.
Deployment: Integrated the trained model into a Power BI dashboard for actionable insights.

# Phase 3: Data Visualization
Tool: Power BI
Dashboard Features:
Revenue trends by year and quarter.
Vehicles sold by state and make.
Predicted vs. actual selling prices and percentage differences.
Key performance indicators to support data-driven decision-making.

# Key Deliverables
Phase 1 & 2 Report:
Comprehensive documentation of the data collection, preprocessing, and model development process.
Phase 2 Summary:
Concise highlights of data preparation, modeling, and evaluation outcomes.
Phase 3 Dashboard:
Interactive Power BI dashboard showcasing sales trends, predictions, and insights.

# Future Enhancements
Expand dataset to include additional variables such as customer demographics and market trends.
Increase data update frequency for real-time predictions.
Incorporate automated data cleaning tools to maintain high data quality.

# Getting Started
To explore this project:

Review the detailed and summary project reports (Deliverable 1 and Deliverable 2).
Interact with the Power BI dashboard for insights on vehicle sales and predictions.
