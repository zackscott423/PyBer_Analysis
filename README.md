# PyBer Analysis

## Overview
For this analysis, ride sharing data from PyBer in 2019 was analyzed across different city types (Urban, Suburban, and Rural).  Metrics including Rides, Drivers, and Fares were evaluated across each of these groups to understand the differences between each, as well as identify any business opportunities to address based on performance gaps between them.  

## Results
There were two key views of the data that were developed to conduct this analysis; 1) a tabular view across the three different city types, and 2) a visual representation of fares over time across these city types.  

### Tabular View of Key Performance Indicators


![PyBer_tabular](Analysis/PyBer_tabular.png)

A few key differences across groups becomes quickly apparent when evaluating the data table.  

* The number of Urdan rides significantly eclipses both Suburban and Rural ride counts (and the same holds true for drivers)
* There appears to be an inverse relationship between number of rides and the average fare per ride (and driver as well)
* Interestingly, there are more drivers than rides in Urban cities, whereas Suburban and Rural cities have more rides than drivers

### Plotting Ride Share Data Over Time

![PyBer_fare_summary](Analysis/PyBer_fare_summary.png)

In evaluating the time period from January through April (in weekly increments), there are a few patterns that emerge.

* There is a spike in fares across all city types in the third week of February, with a subsequent dip in the following week (especially in Suburban cities)
* There is significant volatility in Urban fares throughout March, with swings of around $500 in fares between each week
* There is a stead incline of fares in Suburban cities starting the second week of April through and continuing through the end of the month

## Summary

Based on the observed data, there are three potential actions that could be taken to support the PyBer business:

1. Given the apparent excess of drivers in Urban areas, see if there are ways to shift driver capacity to other areas with higher fares (like Suburban), especially during peak periods like end of April.
1. With the relative lag of fares in Suburban areas in March, and the volatility of fares in Urban areas, it's worth investigating if there's an opportunity to shift Suburban drivers to Urban cties during that period.  A volatile trend could indicate a lack of capacity to serve rider needs during that time period.
1. While the high average fares of Rural rides looks appealing, more investigation should be conducted to understand the profitability of these routes.  These rides were likely longer and incurred more costs for the drivers, but more data needs to be analyzed to confirm.  


