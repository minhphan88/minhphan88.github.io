---
title: "Bitcoins predictions - A Time Series Presentation"
collection: presentations
permalink: /presentations/timeseries
---
## About the project:
  The project is a presentation of a time series analysis.

## Goal
  The project aims to accurately predict the value of bitcoin for the next 10 days using the appropriate time series analysis.

## Data
  The dataset is the daily closing price of bitcoin from the 27th of April 2013 to the 24th of February 2019. Source: coinmarketcap.com

## Presentation
  The presentation covers three main sections:
    1. General observation of a time series.
    2. Model specifications.
    3. Predictions using the most appropriate model.
  The project demonstrates the various steps in a time series analysis:
    1. Trend and Seasonality analysis.
    2. Time series transformations.
    3. Models fitting.
    4. Model Diagnostics
  The project is presented in the folling video
    {% include video id="1jdl9flcZmw" provider="youtube" %}

  The analysis report includes descriptive analysis, proper visualisation, model specification, model fitting and selection, and diagnostic checking.
  You can [downloaded the R markdown report](https://minhphan88.github.io/assets/timeseriesreport.pdf) here.

## What I've learned from this project
    1. Overfitting
      The project is an example of the debate between having an exact fit models versus accurate forecasts. The best fitted model does not have the lowest  forecasting MASE, while the model with the best forecasts (MASE) capacity does not provide the bit fit.

The project demonstrates the ability to work with R libraries including *fGarch,forecast,fUnitRoots, lmtest, rugarch, TSA, x12 etc*

*Note: The presentation used MAE instead of MASE, this was due to a last minute change from the project supervisor*
