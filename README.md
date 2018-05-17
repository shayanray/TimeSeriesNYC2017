# Time Series Analysis of NYC Crimes in 2017

## Abstract:
----------
In this project, we have analyzed the NYPD Complaint Data from NYC Open Data. Our objective is to empower NYPD with exploratory data analysis and predictions so that they utilize their time and energy in the most effective way. That would result in better hot-spot policing(surveillance of crime prone zones), judicious staff deployment across boroughs, time-dependant vigilance and narrow down plausible root-causes in crime trends.


## Introduction:
---------------
New York City or The Big Apple is the most densely populated city in United States as of 2017. Manhattan (a NYC Borough) as we all know is the heart of the 'Big Apple'. It is one of the world's largest commercial, financial , cultural and entertainment centers. The list of eminent buildings and places of interest is endless, therefore its protection is of supreme importance to the nation. Now that makes the job of the NYPD (New York Police Department) astoundingly challenging.
This motivates us to do exploratory crime/complaint data analysis and empower these policemen with effective information to combat crime.


## Topics Covered:
------------------

Predict the number of crimes in NYC boroughs in the next 2 weeks by the hour so that NYPD can deploy staff judiciously across boroughs for the next 2 weeks.

## Methods Implemented: (all done manually other than ARIMA)
-------------------------------------------------------------
1. Seasonal Last Observed: The purpose of the seasonal last observed method is to isolate the recurring trends. In ther words, decompose the series into the trend effect, seasonal effects, and remaining variability.

2. EWMA (Exponentially Weighted Moving Average):It improves on seasonal and moving average methods by assigning weights to the periodic trends.It facilitates using larger data sample size and assigns greater weights to more
recent observations. 

3. AR (Auto-Regression) - Rolling Forecast( Linear Regression used to compute Betas) : It specifies that the output variable depends linearly on its own previous values and on a bias term. Contrary to the moving-average
model, the autoregressive model is not always stationary.

4. ARIMA (Autoregressive Integrated Moving Average) - Rolling Forecast : Non-seasonal ARIMA model has been tried out in this topic. It is denoted by ARIMA (p,d,q) where parameters p, d, and q are non-negative integers, p is the order (number of time lags) of the autoregressive model, d is the degree of differencing (the number of times the data have had past values subtracted), and q is the order of the moving-average model.

