# PyBer_Analysis

## Overview of Analysis

For this project, I will be analyzing and visualizing data for a ride sharing company named Pyber. Using matplotlib, I was able to generate line, bubble and box-and-whisker plots to create insightful visualizations of my data. With the help of Pandas, NumPy and SciPy, I was able to find key measures of central tendency within my data. The initial analysis proved quite useful, as I was able to gain insight on the drivers, fares, and rides done within the ride sharing service. Now I am charged with the task of creating one final dataframe and multiple-line chart that will summarize key trends in affordability, and accessibility of the ride sharing service.

## Results

### Accessibility - DataFrame

  When it comes to accessibility, we must look at the "Total Rides" and "Total Drivers" columns within the dataframe. We can that both the rural and suburban city types have more rides than drivers, however for urban cities we see that we have far more drivers than total rides.

![](Resources/pyber_summary.png)

The contrast between rides and drivers reveals two things to us.
- Greater demand in rural and suburban neighborhoods than supply of drivers.
- Excess supply of drivers in the urban cities.
  
### Affordability - DataFrame:

The rural neighborhoods are also the most expensive place to catch a ride. The average ride in a rural neighborhood cost over $10 more than the urban neighborhood.

- Highest Average Fare per Ride - Rural: $34.62
  - Lowest: $24.53 


### Line Chart of Total Fares 

Our line chart below shows us the total fares by the city type per month for the first 4 months. Here we get a visual confirmation showing that there is far less activity in the rural areas.

![](analysis/PyBer_fare_summary.png)

## Summary

Based on the information we were able to accumulate with this analysis, it is clear where Pyber can make adjustments to improve accessibility and affortability. 

### Table Analysis

Analyzing the summary dataframe revealed that rural and subruban riders had less accessibility to rides. The lack of accessibility in turn lowered the affordability as of our rides in those areas. The issue stems from a lack of drivers to supply the service that our platform offers to the less populated areas.

The solution here can be incentivising drivers in the urban areas to work in the rural areas from time to time. Making urban drivers work in the rural areas would immediately bolster the supply of drivers and drive down the average cost of the ride fares. In the image below we can see a wide margin of almost $40 that would benefit the drivers that do take part in this opportunity.

- Highest Average Fare per Driver - Rural: $55.49 
  - Lowest - Urban: $16.57

Moving drivers from urban to rural and suburban neighborhoods would essentially kill two birds with one stone, as it would increase the accessibility and affordability of our platform. I would strongly recommend reaching out to urban drivers and getting some to work our rural and suburban neighborhoods.

