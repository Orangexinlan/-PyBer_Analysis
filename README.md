# PyBer_Analysis

## Overview of Project
Creating several types of visualizations to tell a compelling story about the data. I will write Pythons scripts using Panda's libraries, the Jupyter notebook, and Matplotlib to creat a variety of charts that showcase the ralationship between the type of city, and the number of drivers and riders, as well as the percentage of total fares, riders and drivers by tupe of city. The final visualizations will help Pyber improve access to ride-sharing services and determne affordability for underserved neighborhoods.

## Results

### From Summary DateFrame 

![this is an image](https://github.com/Orangexinlan/PyBer_Analysis/blob/083a708b500eda2ffdbb94080f2bd692e99ff017/analysis/Summary%20DF.png)

After merging two data sets, we got the data sets for Total Number of Rides , Dirvers and Fares, as well as the average fares for drivers and rides, which falls on the different types of cities.

As the data showed in the output, we can see that in Urban Cities, there are more drivers than rides. In results, Urban Cites is the only type of city with less average fares for drivers than for rides. 

In Rural cites, there is not lots of drivers or rides, but the averages fares are the highest one. Suburban cities is the in the middle of three types of cities.


### From Total Fare by City Type Visualization
![this is an image](https://github.com/Orangexinlan/PyBer_Analysis/blob/083a708b500eda2ffdbb94080f2bd692e99ff017/analysis/PyBer_fare_summary.png)

We pivoted datas into a new DataFrame, and then grouped by weeks to show the total fares by city type. Then I created a multiple line plot to shows the results.

  1. There is a peak for Urban and Suburban citeis happened at the same time, which is close to March. But in Rural City, the peak happened in April. 
  2. After April, fares for both Urban and Rural cities are slowly going down, however the fares for Suburban is going up.
  3. In this visualization, the highest total fares is always Urban cites, and lowest one happened on Rural Cities.


## Summary

From all the outputs, we can easily tell that in Urban Cites, the total fares is the highest. However, when the divers is more than the rides, we need to consider reduce the drivers, too much competion may not cause a good results, or we can see how to expand the business to attact more customers to make the drivers have enough income.

By getting a more accuacy analysis, we can also put Mileage in to the dats collection and process. 
