# TripleTen-Sprint-14-Project
🚖 Time Series: Taxi Demand Prediction — Sweet Lift
📝 Project Overview

This project focuses on predicting hourly taxi orders for Sweet Lift, a taxi company operating at airports. Using historical order data, the goal is to forecast demand for the next hour. Accurate predictions allow the company to attract drivers during peak hours, improve service reliability, and optimize operational efficiency.

The project emphasizes time series modeling, predictive accuracy, and actionable insights, with the target metric being RMSE ≤ 48 on the test set.

📊 Dataset Description

The dataset contains historical taxi order records at airports:

Timestamp of each order

Number of orders per time unit

Key preprocessing steps included resampling the data to hourly intervals, creating a consistent time series suitable for forecasting.

🎯 Objectives

Load and preprocess the data, resampling it by hour

Explore and analyze patterns in taxi demand

Train multiple predictive models with varying hyperparameters

Evaluate models using a 10% test sample

Ensure predictions meet the RMSE ≤ 48 threshold

Provide actionable recommendations for peak-hour driver allocation

🔍 Key Tasks Performed
🧹 Data Preparation

Loaded and inspected the dataset for completeness and consistency

Resampled taxi orders by hourly intervals

Checked for missing timestamps, anomalies, or irregularities in the data

📈 Exploratory Analysis

Visualized hourly, daily, and weekly patterns in taxi demand

Identified seasonal and temporal trends affecting peak periods

Created visualizations to understand variability and forecast drivers

🔧 Model Development

Trained multiple time series models, including:

ARIMA and SARIMA for classical statistical forecasting

Gradient Boosting models for feature-based time prediction

Tuned hyperparameters to improve predictive accuracy

Split the dataset into a training set and a 10% test set for evaluation

Measured training time and prediction speed to assess practical deployment

Note: All models used are traditional time series and regression-based methods. No BERT, transformer-based, or NLP models were used in this project.

📊 Model Evaluation

Evaluated models using RMSE as the primary metric

Compared different model approaches to select the most accurate and efficient

Ensured all predictions met the target threshold of RMSE ≤ 48

Documented trade-offs between model accuracy, training time, and prediction speed

🛠️ Tools & Technologies

Python for programming

Pandas & NumPy for data manipulation and resampling

Scikit-learn for regression and model evaluation

Statsmodels for ARIMA/SARIMA modeling

Matplotlib & Seaborn for visualization

Jupyter Notebook for interactive development and reporting

📈 Final Deliverables

Cleaned and resampled hourly dataset ready for modeling

Trained time series and gradient boosting models with tuned hyperparameters

RMSE evaluation and performance comparison for all models

Visualizations showing demand patterns, seasonal trends, and forecasts

Actionable recommendations for peak-hour driver management

✅ Success Criteria

The project demonstrates:

Proper handling of time series data and hourly resampling

Accurate prediction of taxi demand (RMSE ≤ 48)

Comparison of multiple models with hyperparameter tuning

Clear analysis and actionable business insights

Well-documented and reproducible workflow suitable for deployment

📌 Conclusion

This project illustrates the practical application of time series forecasting in a real-world business scenario. By accurately predicting hourly taxi orders, Sweet Lift can:

Allocate drivers effectively during peak hours

Improve service reliability and customer satisfaction

Optimize operational efficiency and reduce downtime

The approach leverages classical and feature-based time series methods, ensuring predictive accuracy without the complexity of NLP models like BERT.
