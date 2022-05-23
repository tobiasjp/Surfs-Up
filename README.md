# Surf n'Shake

## Overview
W. Avy is an investor looking to open a new surf and ice cream shop on the island of Oahu, with the hopes of expanding to other islands.  Mr. Avy would like to analyze weather data on the island of Oahu, prior to opening the shop.  This analysis will offer Mr. Avy and his board of directors and oppurtunity to analyze the success of the surf and ice cream shop based on weather patterns in the region.  The expectation is the shop is likely to be successful if there are high temperatures and limited percipitation in the region.

## Resources

Software/Languages:
  - SQLite
  - Python
  - Anaconda/Jupyter Notebook

Data:
  - hawaii.sqlite

## Results

### Analysis
Using data collected from Oahu in the form of a SQLite database, we were able to isolate data for two specific months of the year, June and December.  
  - These two months were chosen in order to assess if the Surf n'Shake shop would be viable year round. By isolating these months, we were able to compare the sustainability of a surf shop year round by summarizing temperature statistics for the region, as described below.

### June Results
Based on historic data of weather trends on Oahu, we found:
  - June had a minimum temperature of 64 degrees (F).
  - June had a maximum temperature of 85 degrees (F).
  - June had an average temperature of 75 degrees (F).

### December Results
Based on historic data of weather trends on Oahu, we found:
  - December had a minimum temperature of 56 degrees (F).
  - December had a maximum temperature of 83 degrees (F).
  - December had an average temperature of 71 degrees (F).

### Comparable Results
  - June had a minimum temperature that was 8 degrees higher than December's minimum temperature.
  - June had a maximum temperature that varied little from December, with a variance of 2 degrees.
  - The average temperature between June and December varied by approximately 4 degrees (F).


## Summary
Based on the results of the analysis, we can conclude:
  - The Surf n'Shake shop is likely to be successful all year round.
    - The average temperatures between June and December, varied by approximately 4 degress (F).
    - Lowest temperatures varied by approximately 8 degrees, however, the average temperature for both months are a likely indicator of typical weather for the entire month.
    - Since there is little variance between average temperatures, and little variance between maximum temperatures, it is likely that patrons will want to visit all year round due to the relatively warm temperatures.
 

## Recommendations
Precipitation is another likely factor to consider for the success of the show.
  - By isolating June and December for amount of precipitation instead of average temperature, we can analyze if any particular month may experience heavier rainfalls and how that may correlate to temperatures.  It may be helpful to consider offering additional discounts for months that are particularly rainy.
  - By isolating June and December months and filtering by station where the data was collected, we can analyze the accuracy of the data by identifying stations that collected reliable data about precipitation or even temperatures on Oahu.  The data could also be challenged by only accepting stations that offer at least 1,000 data points, but no more than 2,500.  This could possibly help find trends in the accuracy and predictablity of weather in the Oahu region.
