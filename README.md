# PyBer Analysis
An analysis of a Python-powered rideshare company's driver and city data.

## Overview
As a new data analyst at Pyber, my first task was to use the matplotlib and pandas libraries of python to analyze and illustrate the relationships between the type of city (urban, suburban and rural) and the number of drivers, the number of riders, and the amount of fares. After completing that initial analysis, our CEO V. Isualize gave me two tasks. First I created a dataframe that summarizes the differences between the three city types in terms of the number of rides, the number of drivers and the total fares as well as the average fares per ride and average fares per driver. Then, I created a plot that charts the total weekly fares by city type. The company will then use this data to improve access and affordability in underserved areas. Below are the results of my analysis as well as recommendations for the company.


## Results

From the summary dataframe below, the differences between urban cities and other cities are stark.

![summary of data by city type](https://github.com/LiShanDa2021/PyBer_Analysis/blob/main/analysis/Screen%20Shot%202021-10-11%20at%204.16.41%20PM.png?raw=true)

As you can see, suburban and rural riders pay 6 and 10 dollars more on average per ride than do urban riders. Being a rural Pyber driver, however, is a much better deal. Drivers in rural areas make significantly more per ride than do suburban and urban drivers, and with 1.6 rides per driver they have more chances to get fares than urban (1.48 rides per driver) and suburban (1.28 rides per driver) drivers. The suburbs are ideal for neither drivers nor riders. Suburban riders pay significantly more than urban riders while urban drivers make less than rural drivers and have fewer chances to earn fares. The disparity between urban, suburban and rural cities is also evident in the week-by-week analysis of total fares in the chart below -- although there are some trends that all three city types share.

![week by week analysis](https://github.com/LiShanDa2021/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true)

The chart displays the total fares by week for each city type. Urban total fares are, of course, much higher each week, but you will notice similar patterns across city types with some deviations. All city types begin the year with a lull and then experience a peak in fares in late February. Urban cities then experience a series of peaks and valleys in March while revenues for suburban and rural cities remain relatively low. Urban and rural cities then reach another peak in early April while suburban city fares fall. Urban and rural cities fall again toward the end of April while suburban cities reach a new peak.


## Summary

Based on the data above I would make the following recommendations to V. Isualize in order to improve access and affordability in underserved areas.

* Campaign to recruit rural drivers. There is clearly demand in rural areas as rural drivers have the most rides per driver.
* Incentivize suburban drivers to pick up rural fares -- particularly at times when rural demand is relatively high and suburban demand relatively low. There are fewer rides per driver in the suburbs, so with only a little convincing, suburban drivers may make the trip to rural areas.
* Promote the service to suburban riders. There are drivers available in the suburbs -- but not enough riders. However, many suburbanites may think of ride-sharing as an urban service and may not realize we operate in their area.

