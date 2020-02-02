---
title: "A forecasting example using the Makridakis Competitions data (M3-compressed)"
collection: presentations
date: 2019-11-12
permalink: /presentations/forecasting
---
## About the project:
  The project is a presentation submission for the M3 Competitions (reduced version).

## Goal
  The project aims to evaluate and compare the accuracy of different forecasting methods.

## Data
  International Institute of Forecasters (IIF) runs a competition, called M - Competitions, which is led by forecasting researcher Spyros Makridakis. The aim of the competition is to evaluate and compare the accuracy of forecasting methods over a massive collection of 3003 data series with different characteristics.

  The original dataset is reduced to 1000 series including yearly, quarterly, and monthly micro-economic, macro-economic, industrial, financial, and demographic time series data.

## Presentation
  The presentation of this project covers three parts:

    1. Modelling approach.
    2. Model specification.
    3. Predictions using the most appropriate model.

  The project demonstrates a forecasting analysis using:

    1. Exponential smoothing methods.
    2. Linear Innovations State Space Models.
    3. Nonlinear and Heteroscedastic Innovations State Space Models
    4. Selections of model using various metrics (AIC, BIC, MASE, etc)

  All of these were achieved by creating appropriate customised functions in R to analyse 1000 time series.

  The project is presented in the folling video
    {% include video id="wzn_FPRb9ts" provider="youtube" %}

  You can [download the report](https://minhphan88.github.io/assets/forecastingreport.pdf) here. The details of the code can be found in the Appendix.

## What I've learned from this project
    1. Overfitting:Once a system learns too much from the data, the accuracy of the forecast will reduce due to overfitting. A model MASE does not guarantee good residual diagnostics.
    2. Communication is critical: The fate of a project can be easily altered by mis-communication. In the beginning, I have optimised the system for the forecasting MASE, however, I have changed it to optimise for training MASE due to a mis-communication with the project supervisor.

  The project demonstrates the ability to work with R libraries including *fGarch,forecast,fUnitRoots, lmtest, rugarch, TSA, x12 etc*
