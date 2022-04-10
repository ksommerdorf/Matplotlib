# PyBer Ride Sharing Analysis
## Overview of Project
The data analyst for PyBer, a Python based ride-sharing app company, has requested help in analyzing large data csv files in order to show case the relationship between the type of city and the ride sharing data. The goal of the analysis is to help PyBer improve access to ride-sharing services and determine affordability of underserved neighborhoods. 

## Development Environment 
* Jupyter Notebook
* Python v3.10.4 Dependencies:
  * Python Pandas library
  * Python Numpy library
  * Python Matplotlib.pyplot library 
  * Scipy.stats module

## Resources 
* [city_data.csv](https://github.com/ksommerdorf/Module5Challenge/files/8459969/city_data.csv)
* [PyBer_ride_data.csv](https://github.com/ksommerdorf/Module5Challenge/files/8459970/PyBer_ride_data.csv)
* [ride_data.csv](https://github.com/ksommerdorf/Module5Challenge/files/8459971/ride_data.csv)

## Results

![Fig1](https://user-images.githubusercontent.com/57520471/162641113-97d621c0-e83e-447b-a867-982c56b684a7.png)

Urban cities make up the most total number of rides per city but the lowest average fare amount. On the contrary, rural cities make up the least amount of total number of rides per city and the most average fare amounts.

![Fig2](https://user-images.githubusercontent.com/57520471/162641123-25132b1a-68ae-4a13-8144-07d90b01068c.png)

There outlier in the urban ride count data is West Angela. The average number of rides in rural cities is about 3 to 4 four times lower than the urban and suburban cities.

![Fig3](https://user-images.githubusercontent.com/57520471/162641133-c2edd691-b65d-4e43-87de-90821f39797a.png)

No outliers in the data but the average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities. 

![Fig4](https://user-images.githubusercontent.com/57520471/162641136-5e4bfa41-b71e-4a94-9945-2f1e3b60b150.png)

The median number of drivers in the rural cities is seven times less than the urban cities and three times less than the suburban cities.

![Fig5](https://user-images.githubusercontent.com/57520471/162641148-3a90fa86-a2ba-4a1a-8dab-2c39b83cedf5.png)

Urban cities make almost two thirds of the total number of fares and suburban cities make up almost a third of the total fares. 

![Fig6](https://user-images.githubusercontent.com/57520471/162641172-09384373-5798-4e9c-85a6-32d140fd6b01.png)

Urban cities make more than two thirds of the total number of rides and suburban cities make up about a fourth of the total number of rides.

![Fig7](https://user-images.githubusercontent.com/57520471/162641180-bcf4d88d-3802-4cb8-a203-aeea9c50f2c2.png)

Urban cities make up almost 90% of the total drivers and rural drivers make up less than 1.0% of the total drivers. 

![pyber_summary](https://user-images.githubusercontent.com/57520471/162641314-26db0083-55ef-4283-9d51-44edd3a7d355.png)

* Rural cities have the lowest total of rides but have the highest average fare per ride and average fare per driver.
* Urban cities have the highest total number of rides but the lowest average fare per ride and average fare per driver.
* Rural cities pay an average of $10 more per ride than those in urban communities. 
* In the Urban cities there are 1.5 times more drivers than total rides whereas in suburban and rural cities there are more total rides than total drivers. 
* Urban city drivers make the lowest average fare. Suburban drivers make more than double and rural drivers make more than triple the urban city driver's average fare.

![PyBer_fare_summary](https://user-images.githubusercontent.com/57520471/162641371-35ccc6f1-362d-460e-a2cd-87be25d7dcb8.png)

* Urban cities maintain the highest total fares and rural cities maintain the lowest total fares. 
* In rural cities, total fare values have the highest peaks in the last two weeks of the month.
* In the third week of March all cities experience a peak in total fare amounts.

## Summary
* Even though rural cities make up the least about of total rides, they have the highest average fare value per ride. Riders in rural cities tend to travel farther distances therefore increasing their average fare rate. To help combat this discrepancy, the rate per mile in distances above 15 miles should be lowered. This would allow longer distances to be more affordable. 
* Urban cities on the other hand make up the greatest number of total rides but pay the least average fare value per ride. The rate per mile in the first 15 miles should be higher. This would increase more profit on shorter rides. Also rates in metropolitan urban areas should be increased because of the higher demand. 
* Drivers in urban cities make a significantly less in average fares per ride compared to drivers in suburban or rural cities. Drivers in urban cities also make significantly less in average fare per driver compared ($16.57) compared to the average fare per ride ($24.53). Also, the number of drivers in urban cities is 1.5 times more than the number of total rides. The number of drivers needed should be based on the demand (total rider amount). Therefore, the number of urban city drivers needs to be decreased because there should be more rides than drivers in order for the drivers to make a reasonable income. 
