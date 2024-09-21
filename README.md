## banana-harvest-prediction
This repository contains code and datasets for the project 
## A Deep Neural Network Approach for Enhancing Prediction Capabilities of Banana Harvesting Products
## Project Overview
This project aims to enhance banana production forecasts by leveraging advanced machine learning models. The focus is on improving the prediction accuracy of banana yields in Colombia, which is crucial for efficient resource allocation, market planning, and agricultural management. Bananas are a significant contributor to Colombia's economy, representing 0.4% of the country's GDP and generating approximately USD 730 million annually.

The study compares several deep learning models such as GRU, RNN, Random Forest, XGBoost, Bidirectional LSTM, and Prophet, which show superior forecasting performance compared to traditional models like ARIMA and SARIMA.

## Models Utilized
- Gated Recurrent Unit (GRU)
- Recurrent Neural Network (RNN)
- Random Forest
- XGBoost
- Bidirectional Long Short-Term Memory (LSTM)
- Prophet

These models were used to predict banana production and optimize harvest management. The combination of models allowed for better forecasting, especially in handling complex time-series data with temporal dependencies.

## Dataset Description
The dataset comprises banana production data from 2007 to 2017 across multiple banana farms in Colombia. The following variables were used in model training and evaluation:

- Farm: Identifies the farm where the production took place.
- Year and Week: Denotes the time of production.
- Hectares: Amount of land harvested during the period.
- Actual Packing: Total fruit production.
- Bunches Harvested by Type: Bunches harvested based on week of maturity (Week 8–13).
- Total Harvested: Total bananas harvested during the period.
- Total Boxes: Number of boxes produced.
- Premium Boxes: Number of boxes with premium quality.
- Short Fruit Boxes: Number of boxes with short fruit.
- Company Forecast: Initial forecast provided by the company.

## Key Findings
- Hybrid models (RNN + Random Forest + XGBoost) consistently outperformed traditional ARIMA and SARIMA models.
- GRU and Bidirectional LSTM captured long-term temporal dependencies, improving prediction accuracy for future harvests.
- Prophet model provided effective long-term predictions and uncertainty estimates, making it useful for strategic planning
