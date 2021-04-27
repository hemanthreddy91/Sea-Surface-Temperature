# Climate Change - Data Analysis 

## Overview

Climate change has certainly become one of humanity's greatest threats.  It is defined as the change in global or regional patterns in climate.  Advancements in technology have allowed scientists to collect various types of data regarding our changing planet, which has led to many significant discoveries.

The primary theories we looked into and the objectives we aimed to achieve by analyzing a few selected datasets relate to the effects of global and regional increases in temperature, and its progression due to greenhouse gas emissions.  More specifically:
* Linear and non-linear regressional analysis on average global and regional temperatures
* Geographical correlation to increasing temperatures
* Prediction of carbon dioxide atmospheric concentration
* Impact of fossil fuel combustion, carbon dioxide, and other greenhouse gases

## Pre-processing and Data Exploration


In particular, our datasets were **Time Series**, which are considered data points collected in constant time intervals.  Time series are typically used to observe long-term trends in order to forecast predictions.  However, time series are relatively difficult to work with because they:
> 1. are time dependent, meaning each observation is not independent
> 2. consist of seasonal trends; in our case, temperatures fluctuate between seasons and are not necessarily relevant to long-term climate changes

In addition to our iPython notebooks, there is a python script in which we handle much of the processing, such as extrapolating features, handling missing data, identifying outliers, and plotting.

## Model Fitting and Metrics

We used another open source library [scikit-learn](http://scikit-learn.org/stable) in order to do our model fitting, cross-validation, and predictions.  

The main methods and techniques we used were:
* Linear Regression 
* Discrete Fourier Transform
* Support Vector Machines
 * Support Vector Classification
 * Support Vector Regression
* Kernel Ridge Regression
* Logistic Regression
* K-Nearest Neighbors Classification
* Decision Trees
* Grid Search Cross-Validation
* Gaussian Naive-Bayes
* Confusion Matrix

## End Notes

In this project, we discovered how to approach time series predicting with use of data analytics.  Specifically, we looked into the long-term pattern changes in global and regional climate.  We used statistics and visualization to provide structure and insight into our data, and we used machine learning to fit our data to as many statistical models as we could and evaluated their performance.  

Some of what we learned was how the average surface temperature has been increasing while becoming less varied over the most recent years.  This is likely due to the start of the Industrial Revolution in the mid 1800s.  This explains the sharp increase in average temperatures observed around that time and the decrease in year-to-year standard variance.  Additionaly, our data suggests certain geographic regions, like the Middle East, have been increasing in temperature at a rate faster than the rest of the world, which may have drastic changes on the planet as a whole.

Temperatures continue to steadily increase most likely due to the emissions of certain greenhouse gases from the burning of fossil fuels.  We find that the atmosphere's largest greenhouse gas contribution comes from carbon dioxide, and the concentration of this gas continues to increase, recently breaking 400 ppm (parts-per-million).  Sea levels have also gone up as a result of increased global temperatures, which has adverse effects on sea life and coastal regions.  

## Resources

https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data

https://www.kaggle.com/txtrouble/carbon-emissions

http://www.ncdc.noaa.gov/data-access/quick-links

https://www.nodc.noaa.gov/General/sealevel.html

http://climate.nasa.gov/vital-signs/sea-level/

https://www.epa.gov/ghgreporting/ghg-reporting-program-data-sets

http://cdiac.ornl.gov/
