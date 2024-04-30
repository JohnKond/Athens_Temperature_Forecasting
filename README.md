<h1>Athens Land Temperature Analysis and Forecasting</h1>

Author : Ioannis Kontogiorgakis<br>

Date : February 9, 2023<br>
<br>

## Introduction

This project delves into the analysis and forecasting of land temperature in Athens, Greece, leveraging historical data to gain insights and predict future trends. Through comprehensive analysis, including time series decomposition, stationarity testing, and model evaluation, we aim to uncover underlying patterns and dynamics within the temperature data. Utilizing advanced forecasting techniques, we seek to generate accurate predictions for the temperature over the course of the next year. By combining data analysis with predictive modeling, this study contributes to a deeper understanding of temperature variations in Athens and provides valuable insights for climate monitoring and planning.
<br>
Algorithms tested:
- SARIMA
- XGBoost
- LSTM Neural Network

<br><br>

## Dataset

The dataset was acquired from Berkley Earth, a non-profit organization dedicated to analyzing and disseminating data related to Earth's climate. It contains monthly temperatures for various cities starting from 1900 to 2013. In this study, we will focus on temperatures originated from Athens, Greece.

<br><br>


## Results


<center>

![](https://drive.google.com/uc?export=view&id=1jpNw2RIOmRQzKLaZPsk_9nqYh08SUVJy)

| Algorithm | MAE | MSE | RMSE | MAPE | $r^2$ |
|-----------|-----|-----|------|------|-------|
| SARIMA    | **0.87** | **1.1** | **1.04** | **0.04** | **0.97** |
| XGBoost   | 1.54 | 3.25 | 1.8 | 0.07 | 0.92 |
| LSTM      | 1.94 | 5.22 | 2.28 | 0.09 | 0.88 |

</center>
