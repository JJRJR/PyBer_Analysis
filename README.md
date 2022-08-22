# PyBer_Analysis

## Overview of the analysis
V. Isualize wants us to create a new dataframe showing the differences between total weekly fares by city type. In order to accomplish this, we needed to combine the   two data sets into one dataframe. Once we were able to get the data together, we created a summary depicting the total rides, drivers, fares, average fare per ride and    average fare per driver. Then we created a pivot table and used the resample function to create a multiple line graph that shows the total fares for each week by       city type. The line graph cleanly illustrates how each city type performed by week. 

## Results
- Rural rides and drivers are significantly lower than the suburban and urban city types. 
- Total fares matched the same disparity as the number of rides and drivers per city type.
- The average fare per ride was close with with the top end only being approximately $10 away from the bottom. 
- The average fare per driver has a big gap from the high end to the low end at approximately $30.

![summary_df](https://user-images.githubusercontent.com/108442512/185959133-f3fedbea-2ead-40f2-aa69-da0bc2a3d500.png)
    
![PyBer_fare_summary](https://user-images.githubusercontent.com/108442512/185959196-91f2b34f-9ec3-4c2c-8551-b9d2326b5185.png)

## Summary
After review here are the following recommendations I would give to correct the disparities in the city types.

There are more drivers than there are rides in the urban city type whereas the suburban and rural city types have more rides than drivers. I would consider moving some of the drivers from the urban areas to the suburban and rural areas to balance out the average fare per ride. There may be more ride opportunities in these underserved areas. The line chart also illustrates that there are times of higher demand by city type than other city types from week to week. Another option would be to adjust drivers to different city types based on the demand. Lastly, I would recommend increasing the fare rate in the urban city type. There seems to be a higher demand for rides and by increasing the rates the drivers would earn more and the demand could lower to a more sustainable amount.
