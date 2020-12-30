# PyBer_Analysis

## Overview of the Analysis

This project analyzed ride-share data for the fictional Pyber company (referring allegorically to Uber or Lyft) in the year **2019**.
I analyzed the data given to me based on city type **(rural, suburban and urban cities)** and various data points such as the number of drivers, the fare for each ride and how many rides for each city type. The whole point of the analysis was to visualize the different city types' trends in ridesharing data given the fare totals and number of drivers, etc. and to see if there were any business decisions to be made according to these different data slices.

I created different kinds of visualizations for this analysis, inbcluding pie charts, line charts, boxplots and bar charts (with the bars going vertically and horizontally). The make-believe CEO, V. Isualize assigned me to her make believe employee, Omar, who oversaw my work making the charts. 

## Results

Below is a screenshot of the summary dataframe, resampled to display the data on a weekly basis for ridesharing fare totals for each city type:

![Summary DataFrame](https://github.com/Kyle2Miles93/PyBer_Analysis/blob/main/Summary%20dataframe-weekly.png)

This data is further visualized by the three-way line chart below:

![Line Chart summary visual](https://github.com/Kyle2Miles93/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

According to each, there are many peaks and dips in the fare amounts for each month. However, there were large spikes in fare amounts for the third week of February in 2019. the trends for rural and urban cities follow the same pattern for each month, while the suburban fare totals seem to point in an opposite pattern (with an exception for the month of February): In April, for instance, rural and urban cities experienced a peak while declining throughout the month, while in suburban cities April experienced a dip but then steadily increased throughout the month. Additionally, overall the lines for urban cities and suburban cities follow a slight downward trend, but for rural cities, while pretty consistent, nevertheless follow a slight *upward* trend. 

Urban cities clearly have the highest total fares and rural cities the lowest, which is why rural cities have the highest fare rates per ride, while urban cities have the lowest. Suburban cities fall somewhat in the middle of these two analytics overall.

## Summary

Based on the data analysis, I would recommend charging a bit more for urban and rural cities in the early months of the year: January through March. In April, the fare totals decrease, which tells us that less people are ride sharing during these months. We should capitalize on the higher demand for ridesharing by charging a bit more for those early months. Additionally, in rural cities and urban cities, we should perhaps scale back the prices to incentivize people to use our services, since the data analysis shows that they are using the service less. However, in April for we should **not** scale back fare prices for Suburban cities, because the data shows an opposite trend for these cities.
