# PyBer_Analysis

## Overview

The purpose of this analysis was to quantify the differences in ride-sharing data according to city type (urban, suburban, and rural). In this analysis, datasets with ride-sharing data including city names, ride date, fare amount, and city type were grouped according to city type to compare the number of fares and the amount of fares among the city types over time.

## Results

The results comparing metrics among the city types can be summed up with the following dataframe:

![Summary dataframe with city type data](https://user-images.githubusercontent.com/100863488/161855848-a82ab75b-95e8-4af8-9ad0-19ff5074d40d.png)

This chart reveals that among our data, the vast majority (1,625) of the total rides took place in urban cities, although urban cities had the lowest average fare per ride and average fare per driver. The total rides, total drivers, and total fares are directly positively correlated with the city size, and the average fare per ride and average fare per driver are directly negatively correlated with city size. 

We may assume that these correlations exist because larger cities are more densely populated (more individuals needing rides in a small area, and more individuals available to drive riders) and because there is less distance between places of interest in a dense city than in a rural space (shorter rides lead to lower fares). However, we cannot prove causation from this data; more research would be needed. It is also possible that, depending on how the company compensates its drivers, the higher rural fares might be due to incentives paid to rural drivers to take riders, if rural drivers are scarce.

To illustrate demand over time, we have charted ride data according to city type by week between January and April 2019:

![PyBer_fare_summary](https://user-images.githubusercontent.com/100863488/161856872-cc0dbbad-8897-4e7f-a420-8aefa85f207b.png)

This chart illustrates the difference in total fares among the city types, with the most fares being in the "urban" category and the fewest in the "rural" category. We can observe some trends common to all three (for example, all three city types exhibit peaks in late February).


## Summary

Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

Much more information would need to be gathered to provide compelling reasons to change business practices, but we can make some recommendations based on this data. For example:
   - It would be prudent to learn more about why the rural fares are so much higher than urban fares. Are the higher rates simply a matter of more distance traveled? Are incentives being paid for rural drivers in order to have enough drivers to sustain the service? 
   - In addition, more research should be done on when and why trends occur according to the week and month. Is it possible to correlate the peaks seen in the graph above with specific holidays or other reasons why demand might increase? Is it possible to prepare for anticipated increased demand by incentivizing additional drivers? 
