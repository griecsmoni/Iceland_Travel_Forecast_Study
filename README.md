# Iceland_Travel_Forecast_Study

## Project Overview
[cite_start]The primary objective of this study is to evaluate and compare the performance of two different machine learning approaches—**Random Forest Regressor** and **Long Short-Term Memory (LSTM)** neural networks—in the context of multivariate time-series forecasting[cite: 1, 26]. [cite_start]The evaluation is conducted using historical meteorological data from North Iceland, specifically the Akureyri region[cite: 15, 29].

## Technical Focus
* [cite_start]**Model Evaluation:** A comparison of how a traditional ensemble method (Random Forest) and a deep learning architecture (LSTM) capture complex temporal dependencies in weather data[cite: 1, 352, 361].
* [cite_start]**Weather Forecasting:** Predicting temperature, precipitation, cloud cover, and wind speed based on historical observations from 2000 to 2026[cite: 19, 29, 30].
* **Custom Feature Engineering:**
    * [cite_start]Development of **activity-specific environmental thresholds** (e.g., wind limits for whale watching, cloud cover for Aurora visibility)[cite: 35, 43, 51].
    * [cite_start]Implementation of **sine-cosine transformations** for circular variables like wind direction[cite: 374, 441].
    * [cite_start]Use of **lag features** and temporal variables to enhance model stability[cite: 369, 443].

## Practical Application (Side Product)
[cite_start]As a functional application of the models, the study identifies **favourable travel periods for North Iceland** between **1 March 2026 and 28 February 2027**[cite: 7, 24]. 

By applying the activity-specific criteria to the forecasts, the project estimates optimal windows for:
* [cite_start]**Northern Lights observation**[cite: 518, 537].
* [cite_start]**Whale watching**[cite: 517, 536].
* [cite_start]**Diamond Circle and Hiking**[cite: 519, 536].
* [cite_start]**Skiing and Golf**[cite: 519, 537].

## Key Results
[cite_start]The study concludes that the **LSTM model substantially outperforms Random Forest**[cite: 487]. [cite_start]While Random Forest showed signs of overfitting, the LSTM architecture effectively captured the temporal dynamics of the meteorological data, providing significantly lower prediction errors[cite: 385, 463, 488].

---
[cite_start]**Author:** Monika Griecs-Farkas [cite: 2]  
[cite_start]**Date:** 09/03/2026 [cite: 3]
