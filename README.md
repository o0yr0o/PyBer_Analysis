# PyBer Analysis with Matplotlib

## Overview
PyBer is a ride-sharing app company valued at $2.3 billion. The rideshare data is required to be analyzed from January to early May of 2019 based on different city types.

First, a summary DataFrame of the ride-sharing data by city type needs to be created. Then, a multiple-line graph that shows the total weekly fares for each city type is required. I am assigned to summarize how the data differs by city type and provide some recommendations on the data.

## Results

### Summary DataFrame by City Type
![PyBer_summary](https://user-images.githubusercontent.com/82549782/120053739-fdc15580-bff9-11eb-9d14-9ebf47a0e89d.png)
According to the statistics, urban has the largest number of drivers, rides and fares. 

Although urban has the highest total fares, the average fare per ride for suburban and rural is higher than urban. This may be because many people who live in suburban and rural choose to go to urban for working or shopping, so each ride will be longer and the average fare per ride will be higher. 

The reason that urban has the lowest average fare each time is because they can buy everything they need  in the surrounding area, and urban public transportation is more developed, most people will choose to use relatively cheap public transportation. 

Although rural has the lowest total rides, it has the highest average fare per driver. Because rural has the least number of drivers, therefore, the average fare is higher.

### Multiple-line Graph on Total Weekly Fares for Each City Type
![PyBer_fare_summary](https://user-images.githubusercontent.com/82549782/120053355-a9b57180-bff7-11eb-8df6-671d17b1b984.png)
The total weekly fare of Urban in all time periods is higher than suburban and rural. The total weekly fare of each city type was relatively low in January, and increased at the end of February. In general, the total weekly fare of each city type in the first quarter of 2019 is relatively stable.

## Recommendations
- Due to the higher demand for long-distance rides in rural and suburban areas, and often because the fare of long-distance rides is too high, they would choose not to use PyBer. We can provide discounts to remote users in suburban and rural, so that price-sensitive users would choose to use PyBer.
- For PyBer, drivers are also an important part. Many drivers are reluctant to take long-distance ride orders. This may be because long-distance ride orders are more fuel-intensive or it is inconvenient for them to get off work. PyBer can encourage drivers to take more long-distance ride orders through subsidies.
- Based on the urban data, the number of drivers is much larger than number of rides, so that the fare received by each driver is not high enough, which forms a vicious circle. In order to increase users in urban area, PyBer can provide first-ride coupon for new users in urban area. Furthermore, PyBer can send coupon to old users and new users if old users refer the app to the new users.
