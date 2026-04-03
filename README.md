# Iceland_Travel_Forecast_Study (empirical study)

## Project Overview
The primary objective of this study is to evaluate and compare the performance of two different machine learning approaches—Random Forest Regressor and Long Short-Term Memory (LSTM) neural networks—in the context of multivariate time-series forecasting. The evaluation is conducted using historical meteorological data from North Iceland, specifically the Akureyri region.

## Technical Focus
Model Evaluation: A comparison of how a traditional ensemble method (Random Forest) and a deep learning architecture (LSTM) capture complex temporal dependencies in weather data.

Weather Forecasting: Predicting temperature, precipitation, cloud cover, and wind speed based on historical observations from 2000 to 2026.

## Custom Feature Engineering

Development of activity-specific environmental thresholds (e.g., wind limits for whale watching, cloud cover for Aurora visibility).

Implementation of sine-cosine transformations for circular variables like wind direction.

Use of lag features and temporal variables to enhance model stability.

## Practical Application (Side Product)
As a functional application of the models, the study identifies favourable travel periods for North Iceland between 1 March 2026 and 28 February 2027.

By applying the activity-specific criteria to the forecasts, the project estimates optimal windows for:

- Northern Lights observation

- Whale watching

- Diamond Circle and Hiking

- Skiing and Golf

## Key Results
The study concludes that the LSTM model substantially outperforms Random Forest. While Random Forest showed signs of overfitting, the LSTM architecture effectively captured the temporal dynamics of the meteorological data, providing significantly lower prediction errors.

### Author: Monika Griecs-Farkas

### Date: 09/03/2026
