# PyBer_Analysis

## Project Overview
Overview of the analysis: Explain the purpose of the new analysis.
The purpose of this analysis was to understand the difference between ride sharing performance by city type (Urban, Suburban, Rural) . In this project, I created a summary table of the ride sharing data by city type which includes metrics like total rides, total drivers, total sum of fares, and average fares. To get a better understanding of the difference in fares by city type, I also created a trended line chart to show trends of the average fares by city type.

## Resources
- Data Source: city_data.csv, rides_data.csv
- Software: Python 3.7 (Pandas, Matplotlib)

## Results
Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

**Summary Table**
![City Type Summary Table](https://github.com/jinnabelle/PyBer_Analysis/blob/main/Summary%20Table.png)
<br>
**Total Rides<br>**
Urban cities had the most total rides across the three city types with 1,625 rides. Suburban cities had the second most total rides with 625 rides and Rural cities saw the fewest rides with 125. 

**Total Drivers<br>**
Urban cities saw the most drivers across the three city types with up to 2,405 drivers. Sururban cities had the second most drivers with 490 drivers and Rural cities saw the fewest drivers with 78 drivers.

**Total Fares<br>**
Because of its high total rides, Urban cities received the most fares with a total of $39,854.38. Urban cities are followed by Suburban cities collecting the second most fares with $19,356.33. And finally, rural cities received $4,327.93 in fares. 

**Average Fare per Ride<br>**
For consumers, it is beneficial to learn about how fares are by city type. Below is a summary of which city type has the least and most expensive average fare per ride by city type. The city type with the highest average fare per ride is rural. Rural cities have an average fare of $34.62 per ride. Then followed by Suburban cities with an average fare of $30.97 per ride. Rural cities had an average fare per ride of $24.53.

**Average Fare per Driver<br>**
On the driver side, drivers in urban areas have an average fare of $55.49 per driver. In Suburban cities, they can expect an average fare of $39.50 per driver. And in rural cities, the average fare per driver is $16.57 and this is due to the high volume of drivers in the area.

**Weekly Average Fare by City Type**
![Weekly Average Fare by City Type](https://github.com/jinnabelle/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)<br>
The trended chart above shows the weekly total fares by city type (Rural represented in blue, Suburban represented in red and Urban represented in yellow). The chart shows total fares from Jan 2019 to Apr 2019. <br>
With this trended chart, you can clearly see the difference in total fares collected by week in each city type. Urban cities collected the most fares by week compared to the two other city types. All city types saw an increase in fares collected towards the tail-end of February, which is the only type they had the same behavior.Suburban cities saw an upward trend in fares after the first week of April while the other two types saw an downward trend.

## Summary
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
Business recommendations to the CEO: <br>
1. Increase number of drivers in the Rural cities. Rural cities has the fewest number of drivers in these areas. This will most likely increase ride volume in the area.
2. Increase the ride rate for the Urban cities as they have the lower average fare per ride compared to the other two city types. This, too, in return would also increase the average fare per driver.
3. Decrease the ride rate in the Rural cities. Rural areas have the highest fare compared to the other two city types and this might be causing the low ride volume.
