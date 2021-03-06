# PyBer Analysis

## Overview of Analysis: 

The purpose of the analysis was to use the ride, driver and city data to glean insights into the business
and see if there was a way to optimize profits for PyBer.


## Pyber Analysis Results:

### Ride Summary By City Type:

![RIDE SUMMARY BY CITY TYPE](https://user-images.githubusercontent.com/68127033/90998580-72aabf00-e592-11ea-94c4-f40aece0739f.PNG)

The majority of the revenue generated by PyBer for the period in question came from urban rides, which accounted
for almost 70% of the total rides, and more than 60% of the fares generated.  Rides in rural cities had much better
outcomes on a per unit basis, with the highest average fare per ride of any city type ($34.62/ride.)  Drivers in
rural cities also fared much better than their suburban and urban counterparts, earning an average of more than $55
per ride.  This was 40% more than suburban riders, and almost 2.5x more than urban drivers.

### PyBer Fare Summary:

![PyBer_fare_summary](https://user-images.githubusercontent.com/68127033/90998575-70e0fb80-e592-11ea-8f8d-bed96b68fd1c.png)

The above chart shows total fares for the 3 city types over a 4-month period in 2019.  The trends established
by the first graph are confirmed here.  Urban rides generated significantly more revenue than suburban and rural rides
combined.  While all 3 datasets have small peaks and troughs, timing doesn't seem to have a significant effect on the
performance of the city types; the main driver of overall performance appears to be volume.
    

## Summary:

### Recommendation #1:
Supply and Demand appear to be driving the discrepancy in the per-driver data between groups.  The excess of urban drivers
is keeping their average fare per ride depressed.  The other two city types have less drivers than rides, while the
opposite is true for the urban group.  The first recommendation would be to reduce the number of drivers in the urban
cities to be more in line with the ride demand.

### Recommendation #2:
Reason would also suggest that average fare per ride is higher in rural and suburban cities due to the general lack of public
transportation in these locales, as well as the generally increased distances needed to travel between destinations.  The 
number of drivers should be gradually increased to take advantage of the excellent per-unit averages in those city types, 
with a close eye on the average fare so as not to flood the market with an excess supply of drivers and depress the earnings.

### Recommendation #3:
The final recommendation would be to leverage the ride data (which has date as well as time), to establish a pattern for ride
demand in each city throughout the day.  Efforts should be made to keep the number of available drivers in line with the number
of projected rides for that city at that particular time of day to maximize efficiency.
