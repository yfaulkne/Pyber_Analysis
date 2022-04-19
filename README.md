# Pyber_Analysis
---
## Purpose
##### The purpose of this project was to analyze data for Pyber, a ride sharing service, across different cities in 2019. The data was merged into one dataframe that consisted of Pyber riders, the different cities that they lived in, total Pyber drivers in those cities, and the fares for each ride. There were two deliverables.
#####
* Deliverable 1 was to create a summary dataframe with an index of city type. The three city types were Rural, Suburban, and Urban.
* Deliverable 2 was to create a multiple line plot that shows the weekly total of the fares for each city type. The data was grouped by type of city as well as the dates of each ride.
---
## Results
---
#### Deliverable 1:
#####
Rural Cities 
  * Cities identified as a Rural type had a total of 125 rides during the timeframe of data collection. There were a total of 78 drivers that collected a total of $4,327.93. The average fare per ride was $34.62 and the average fare per driver was $55.49.
#####
 Suburban Cities
  * Cities identified as Suburban had a total of 625 rides during data collection. There were a total of 490 drivers that collected fares totaling $19,356.33. The average fare per ride was $30.97 and the average fare per driver was $39.50.
#####
Urban Cities
  * Cities identified as Urban had a total of 1,625 rides during data collection. There were a total of 2,405 drivers that collected fares totaling $39,854.38. The average fare per ride was $24.53 and the average fare per driver was $16.57.
![](https://github.com/yfaulkne/Pyber_Analysis/blob/main/analysis/pyber_summary_df.png)
---
#### Deliverable 2
##### The fares for each city type were grouped into weekly data using the resample function. The sum of each week from 1-1-2019 through 4-28-2019 are shown below.
![](https://github.com/yfaulkne/Pyber_Analysis/blob/main/analysis/pyber_weekly_pivot.png)
##### The results of that dataframe were then plotted into mulitple a line graph, with Fares on the y-axis and the wekkly dates as the markers on the x-axis.
![](https://github.com/yfaulkne/Pyber_Analysis/blob/main/analysis/Pyber_fare_summary.png)
---
#### Summary
##### In the ride-share data collected, Urban cities had the most rides and drivers across all months. Rural cities had the least rides and drivers in those cities. Suburban cities fell in the middle on both metrics. 
---
##### To address these disprities among the different city types, I would recommend Pyber to run a promotion for discounted rides among Rural and Suburban riders. There seem to be more than enough drivers for both of these city types but the average fares per ride are $6-10 respectively as compared to rides in Urban cities. Rural customers may be discouraged from using Pyber due to these prices.
--- 
##### Using this same promotion, Pyber can also increase metrics for total rides aas well as total fares for Suburban cities. Promotion deals will bring back more loyal customers that already use Pyber as well as encourage new customers to join. As a result, total rides and total fares will increase which will be a win for Pyber.
---
##### Addressing another metric, there is a significant amount of drivers in Urban cities as compared to the total rides. There seems to be too many drivers and not enough rides being given. Pyber can recommend drivers travel to the Suburban or Rural areas during the promotion to increase drivers in those areas and ultimately putting more money in the drivers' pockets.

