# Pyber - Analysis of Ride-sharing data

## Project Overview
For this project I analyzed ride-share data from 2019 in 120 cities. These cities have been divided into three categories: urban, suburban and rural. The goal of the project is to provide an assessment of how these three types of cities differ by looking at relationships between fares, number of rides, and number of drivers across the three categories

## Results

#### The results of the analysis are summarized in the following table.

|          |   Total Rides |   Total Drivers | Total Fares   | Average Fare per Ride   | Average Fare per Driver   |
|:---------|--------------:|----------------:|:--------------|:------------------------|:--------------------------|
| Rural    |           125 |             537 | $4,327.93     | $34.62                  | $8.06                     |
| Suburban |           625 |            8570 | $19,356.33    | $30.97                  | $2.26                     |
| Urban    |          1625 |           59602 | $39,854.38    | $24.53                  | $0.67                     |

1. The total number of rides in urban cities is more than 10 times the number in rural cities, while suburban cities had 5 times the number of rides as rural ones. 

2. There are more than 100 times as many drivers in urban cities as rural ones. There is a much more modest difference in suburban cities, with 16x as many drivers as in rural cities.

3. The sum of all fares in this period was significantly higher in urban cities compared to rural ones, but it is less than a 10 fold difference, with suburban cities having almost 5 times the total of fares. 

4. The average fare per ride is highest in rural cities, somewhat less in suburban, and less even in urban cities.


5. When we divide the total fare by the number of drivers, the difference in number of drivers leads to a very large difference in average fare.


6. Overall, urban rides accounted for nearly two-thirds of the total fare, with rural rides then accounting for less than 7%. 

![Pie chart](analysis/Fig5.png)


7. A chart of the time course for the first quarter of 2019 demonstrates that the differences in total fare between city types is consistent across time. 

![line chart](analysis/Fig6.png)

