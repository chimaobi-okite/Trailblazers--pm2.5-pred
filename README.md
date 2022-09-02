# Trailblazers Zindi Competition

## Context
You may have seen recent news articles stating that air quality has improved due to COVID-19. This is true for some locations, but as always the truth is a little more complicated. In parts of many African cities, air quality seems to be getting worse as more people stay at home. For this challenge we’ll be digging deeper into the data, finding ways to track air quality and how it is changing, even in places without ground-based sensors. This information will be especially useful in the face of the current crisis, since poor air quality makes a respiratory disease like COVID-19 more dangerous.

## About 
The objective of this challenge is to predict PM2.5 particulate matter concentration in the air every day for each city. PM2.5 refers to atmospheric particulate matter that have a diameter of less than 2.5 micrometers and is one of the most harmful air pollutants. PM2.5 is a common measure of air quality that normally requires ground-based sensors to measure. The data covers the last three months, spanning hundreds of cities across the globe.

## Data
We’ve collected weather data and daily observations from the Sentinel 5P satellite tracking various pollutants in the atmosphere. Your goal is to use this information to predict PM2.5 particulate matter concentration (a common measure of air quality that normally requires ground-based sensors to measure) every day for each city. The data covers the last three months, spanning hundreds of cities across the globe.

see more @[zindi](https://zindi.africa/competitions/be-a-trailblazer-nigeria/data)

## Summary Of Results
| Model                                | RMSE        | STD |
|--------------------------------------|------------|-----------|
|Dummy Regressor (Base model 1)       | 46.827        |3.392|
|RandomforestRegressor (Base model 2)       | 37.197  |3.450|
|Xgboost Regressor with FE       | 32.793        |3.077|
|LightGBM with FE       | 31.774        |2.962|
|Hand-tuned LightGBM with FE       |31.565      |2.974|

