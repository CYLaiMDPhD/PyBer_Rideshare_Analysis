# PyBer Rideshare Analysis

*Note: This repository was generated to fulfill assignments (Module 5 Exercises and Challenge) for the UC Berkeley Data Analytics and Visualization Bootcamp. The analysis, content, and format of this report were based on the grading rubric.* 

*Module exercises as demonstrated in notebooks matplotlib_practice.ipyhb, matplotlib_practice2.ipynb, PyBer_ride_data.ipynb, and PyBer.ipynb include:*

- *Installing and using matplotlib*
- *Creating basic charts (line, bar, scatter, pie, box plots) with matplotlib*
- *Creating charts using MATLAB and object-oriented approaches*
- *Annotating and formatting charts*
- *Data manipulation and analyses using pandas*
- *Creating Bubble Charts*


*The report below is based on code and analyses from PyBer.ipynb and PyBer_Challenge.ipynb.*


## Overview

This report summarizes fare and ridership performance across three different city types for a fictional rideshare company, PyBer. Based on some basic analysis, recommendations for executives are discussed.

**Data Source:**
- Data were provided as csv files (Resources/city_data.csv and Resources/ride_data.csv) as part of course materials.

### Purpose
We performed an anlysis of ride share data for our client at PyBer to evaluate ride and fare data across three different city types, urban, suburban, and rural. Using data provided by PyBer covering ride data from 2019, we analyzed driver counts, ride counts, and total fares to help gain insight into how to improve revenues with the platform. 


---

## Results

The overall data for 2019 is summarized below (Figure 1) as a bubble scatter plot with the size of bubbles representing driver counts in each particular city. Trends evident in this graph include:
- The average fares are highest for rides in rural cities, and lowest for rides in urban cities.
- The highest number of rides occurred in urban cities.
- Urban cities tend to have more drivers.


**Figure 1: Scatter plot of Average Fare vs Total Rides per City**
![Fig1.png](/Analysis/Fig1.png)


While all variables of the 2019 data are represented in figure 1, it does not easily display comparative data of total fares or ride and driver statistics. Thus, we plotted ride counts, driver counts, and fare data by city type in the sections below for further analysis.

### Rides

Figure 2 below displays the number of rides per city as box and whisker plots for urban, suburban, and rural cities. Urban cities had the most number of rides, with an average of 24 rides per city. Rural cities had the lowest average ridership at 6 rides per city. The standard deviation was largest for urban cities. Overall, urban cities accounted for the vast majority of rides on the platform. 68.4% of all rides were in urban cities while 26.3% and 5.3% of rides were in suburban and rural cities respectively (Figure 3). 

**Figure 2: Ride Counts for Urban, Suburban, and Rural Cities**
![RidesBox.png](/Analysis/RidesBox.png)



**Figure 3: Percentage of Rides in Urban Suburban, and Rural Cities**
![RidesPie.png](/Analysis/RidesPie.png)


### Drivers

Trends for number of drivers matched trends for number of rides by city type. Urban cities also had the highest number of drivers, averaging 36 drivers per city (Figure 4). However, the standard deviation in urban cities was much higher with the number of drivers ranging from as few as 3 to as many as 73. Suburban and Rural cities averaged approximately 16 and 4 drivers per city respectively. Overall, drivers in urban cities accounted for more than 80% of all drivers on the platform for the analyzed period (Figure 5).

**Figure 4: Driver Counts for Urban, Suburban, and Rural Cities**
![DriversBox.png](/Analysis/DriversBox.png)


**Figure 5: Percentage of Drivers in Urban Suburban, and Rural Cities**
![DriversPie.png](/Analysis/DriversPie.png)


### Fares

Average fares showed an inverse trend compared to the number of rides and drivers. Rides in rural cities cost the most, at an average of $34.62, while rides in urban cities averaged $24.53 (Figure 6). As a percentage of total revenue for the time frame analyzed (2019), fares from urban cities accounted for 62.7% of total fares while rural cities accounted for only 6.8% of the total fares (Figure 7). 

**Figure 6: Fares for Urban, Suburban, and Rural Cities**
![FaresBox.png](/Analysis/FaresBox.png)


**Figure 7: Percentage of Fares in Urban Suburban, and Rural Cities**
![FaresPie.png](/Analysis/FaresPie.png)


---

## Summary

**Table 1:**
![table1.png](/Images/table1.png)

Table 1 above summarizes total fares, rides, and drivers for the three different city types analyzed. Overall, rides in urban cities generated to most total revenue (nearly $40,000.00) for PyBer despite having the lowest average fare per ride and per driver. The sheer volume of rides resulted in roughly two times more revenue over suburban cities and nine times more revenue over rural cities. This trend held true when fare data was analyzed over time as weekly totals (Figure 8).


**Figure 8: Total Fares for Urban, Suburban, and Rural Cities Weekly from January through April 2019**
![PyBer_fare_summary.png](/Analysis/PyBer_fare_summary.png)



While this  data implies some association between average fares and total number of rides and drivers, we do not have data about ride distance, which also likely factors in to ride fares. However, based on our analysis above, increasing ridership and number of drivers in rural and suburban cities may lead to generating more revenue in these areas by increasing the volume of rides. Any proportional decrease in the average fare likely will be countered simply by increasing number of rides. 

Our recommendations for increasing overall revenue from suburban and rural cities include:
1. Increase fares for each ride to the maximum tolerated by the market.
2. Increase the number of drivers through outreach and incentives.
3. Increase the number of riders through advertising and rewards.



