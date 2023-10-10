# CITI-BIKE-FORECASTING Data Science at Scale Final README

## Introduction
The project aims to develop a data-intensive application that tracks the inventory of bikes and available docks at a specific station within the Citibike Bike Sharing system in NYC. The goal is to forecast and ensure smooth operation of the system, similar to the Bike Angels application.

## Objective
To develop an end-to-end application that can forecast the inventory of bikes and docks at the assigned station, helping in the efficient management of the bike-sharing system.

## Project Components
1. **Extract Transform Load (ETL)**:
   - Refine raw bike and weather data into bronze, silver, and gold levels.
   - Define schemas, partitioning, and Z-ordering.
   - Create immutable ETL pipelines.
   
2. **Exploratory Data Analysis (EDA)**:
   - Analyze monthly and daily trip trends.
   - Investigate the impact of holidays and weather on system use.

3. **Modeling and MLOps**:
   - Build a forecasting model for net bike change by the hour.
   - Register the model in Databricks and store artifacts in MLflow.
   - Tune model hyperparameters.

4. **Application**:
   - Store inference and monitoring data in a gold data table.
   - Monitor staging vs. production model performance.
   - Archive and promote models as needed.
   - Display real-time data, forecasts, and performance metrics.

## References
- [Citibike NYC](https://citibikenyc.com/)
- [Bike Angels](https://citibikenyc.com/bike-angels)
- [Class GitHub Repo](https://github.com/lpalum/dscc202-402-spring2023)
- [Databricks Repo Documentation](https://docs.databricks.com/repos/index.html)
- [Citibike System Data](https://citibikenyc.com/system-data)
- [OpenWeatherMap API](https://openweathermap.org/api/one-call-api#hist_parameter)
