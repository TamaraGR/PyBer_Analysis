# PyBer_Analysis

## Overview

This is an analysis of a car rides company/mobile application PyBer's performance between the months of January and May of the year 2019. In this analysis we are looking into the application's total number of rides, drivers, the total amount of fares, the average amount of payment per each ride and total weekly fares for each city type, including urban, suburban and rural cities. This analysis also includes a chart that summarizes each type of city's totals and averages and a line graphic that depics the weekly total fares for urban, suburban and rual cities. The said analysis aims to provide the PyBer application leadership with summaries of how this data is different depending on the city type. The analysis is followed by some additional recommendations for the application company to look into further analysis of the influencing indicators with the hope that the leadership can use them for the betterment of their service. 

## Resources 

- [x] This analysis is referencing the PyBer_Challenge_stater_code ipynb file. 
 - [x] The code was written and debugged in Jupyter Notebook with the help of Panda and MatPlotLib dependencies (to augment Python analysis).
 - [x] This analysis is pulling from the ![city_data.csv](https://github.com/TamaraGR/PyBer_Analysis/blob/main/Resources/city_data.csv) and ![ride_data.csv](https://github.com/TamaraGR/PyBer_Analysis/blob/main/Resources/ride_data.csv) files. 

## Analysis

Below you are presented with the descriptive summary of the urban, suburban and rural rides, drivers, fares, average fare per ride and average fare per driver. 

![PyBer_summary_df.jpg](https://github.com/TamaraGR/PyBer_Analysis/blob/main/analysis/pyber_summary_df.jpg)

Urban rides constitue 68% of all rides, while suburban take up to 26% and rural 5%. The number of urban rides is 2.6 times higher than the number of suburban and 13 times higher than the number of rural rides. Urban drivers constitue 80% of all drivers, suburban drivers are at 16% and rural at 2.6%. Urban city drivers count is 5 times higher than suburban cities' and 31 times higher than rural count. 

In the suburban and rural cities during the described period each driver took more than one ride. In the urban cities some drivers didn't take rides at all, as their number is higher than the total number of rides. Hence we could assume that abundance of available drivers results in lower fares (as we can see from urban fares versus rural and suburban fares), however, we can't make that assumption without knowing the time and the distance spent per each ride. 

Urban cities made 62.7% of the fares, while suburban made 30.5% and rural made 6.8%. Average fare per ride is the lowest for the urban cities, and for the rural cities it is the highest. Average urban fares per driver are lower by 58% than suburban and 70% than rural. 

The overall PyBer fare summary is presented in the image below:

![Pyber_fare_summary.png](https://github.com/TamaraGR/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

This line graphic is depicting the fares for the months of January through May of 2019, and it looks at the urban, suburban and rural cities' fare data. Pretty much each week the urban cities had higher fares with suburban and rural following. An interesting spike in fares is demonstrated in the second part of February, where we see parallel spike for every city category. 

## Recommendations Summary 

Some of analysis additional recommendations include the following:

- [x] Look at gathering information regarding rides statistics by average length of each ride in terms of time and distance. 
- [x] Look at some of the better performing cities among each city category and try to understand why those cities perform better. 
- [x] Look at ride dencity/price/distance/time spent on a ride during regular and peak times, weekdays versus weekends.
- [x] Look at customer demographics, incluidng gender, age, ethnicity to see if that has anything to do with the performance. 
- [x] Look into public transportation services frequency for each city type, including places with exceptionally good and bad public transportation service, see how that data affects PyBer's riding statistics. 

