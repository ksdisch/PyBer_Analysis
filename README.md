# PyBer Analysis

## Project Overview

### Purpose
The purpose of this analysis was to compare rural, suburban, and city PyBer data. First, we were to sort the data by city type. Next, generated a summary dataframe showing total rides, total drivers, total fares, average fare per ride, and average fare per driver for each city type. Finally, we found the total sales by week between 2019-01-01 and 2019-04-08 for each city type and generated a multiple line chart using matplotlib.

### Resources
- Data Source(s): city_data.csv, ride_data.csv
- Python3.7 anaconda4.13

## Results
### City Type Summary
The dataframe below is a summary of the comparison of PyBer ride, driver, and fare data between urban, suburban, and rural city types. As expected, the urban cities had the highest total number of rides, drivers, and fares and the rural cities had the lowest totals. However, the exact opposite is true for the averages, with rural cities having the highest average fare per ride and the highest average fare per driver. 
![City Type Summary](/analysis/summary_df.png?raw=true "Title")

### Weekly Sales by City Type (January 2019 - April 2019)
The line chart below is examining total weekly fares by city type starting on January 1st, 2019 and ending April 29, 2019. The totals are the highest in urban cities and lowest in rural cities, which is to be expected given that urban cities account for the highest number of rides and rural the fewest. The trends for each city type are relatively similar. Each city type had a spike in total fares in late February. Urban cities spiked again in early March whereas suburban and rural cities remained mostly constant. Suburban cities spiked during the last two weeks of April whereas urban and rural cities slightly declined. 
![City Type Weekly Sales Jan-Apr](/analysis/PyBer_fare_summ.png?raw=true "Title")

## Summary
Based on the results of this analysis, I have three recommendations to address disparities amongst the city types.

### Increase Suburban Fare Prices Substantially
In the summary dataframe, we see that the average fare per ride and per driver is much higher in rural cities than in suburban cities and urban cities. This shows that people are willing to pay more for our rides than we currently charge them. Given that we do not have as much competition with taxis in suburban cities as we do in urban cities, I believe we can raise the fare prices significantly in suburban cities.

### Increase Urban Fare Prices Moderately
As I mentioned the average fare per ride and per driver is much higher in rural cities than in suburban cities and urban cities. However, there is more competition with taxis and other ride sharing companies in urban cities. Because of that, I believe we have to be more careful with increasing our prices in urban cities, because if we go too far we will lose a lot of business to our competitors. We should start with a slight increase, and if we do not see a dip in total rides, gradually continue to increase.

### Run a Promotion in January
We can see in the line chart that our fare totals for all city types are low at the beginning of the year. This is to be expected, as people have just finished spending a lot of money during the holidays and there are New Year's resolutions to be more conservative, not go out at night, etc. Given that it is a poor week for us at the very beginning of the year, I think we would benefit from running a promotion during this time. People will spread word of this promotion to their friends and family, and then when people start going out again later in the year, we will be established as their ride sharing company of choice.
