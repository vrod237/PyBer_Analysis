# PyBer_Analysis

#### The purpose of this Data Analysis is to create a summary DataFrame of the key metrics involved for the ride-sharing data by city type, and by creating a multi-line graph that shows the total fares of each week by each city type. In addition, this will include a written report on the results of the new analysis and future recommendations. I analyzed the data by reviewing the information of each City and City Type and then created a new dataframe by City Type and got the Total Number of Drivers, Total Rides, Total Fares, Average Fare per Ride and Average Fare per Driver, for each City Type of Urban, Suburban and Rural. By reviewing the dataframe below, the information tells us that the Urban City Type had the most amount of drivers, rides and total fares on the flip side; Rural City Type had the least amount of drivers, rides and total fares. In the Total Fare by City Type graph, the Urban line (yellow) shows the highest sum of fares, Rural line (blue) shows the least sum of fares, which reflects what we observed earlier in the dataframe.

- Summary Data Frame
![Summary DF](https://github.com/vrod237/PyBer_Analysis/blob/master/summary_df.png)
- Total Fare by City Type Graph
![Challenge Chart](https://github.com/vrod237/PyBer_Analysis/blob/master/Challenge.png)

#### I came across issues with the techincal analysis since I was not familiar with the process of creating graphs and using pivot tables in Python. But I was able to connect all the dots after reading a few articles after a few quick Google searches. Google is a huge help, especially when it comes to coding, there's so much information out there and there's a good chance the someone has already asked a question you may have. 

#### I would recommend that future data include population size of each City so we can get a sum of the population per City Type and see what trends we can discover regarding the different sizes. For example, Rural areas have the highest average fare per ride and driver, this is likely due to individuals in Rural areas having to take longer rides to get to their destination since they don't live in a major city. Since they don't live in a major city, the lower amount of rides would likely reflect the smaller population size compared to Urban and Suburban City Types. To further prove that, it would help to have pick up time and drop off time added in future data sets. In attaining this data, we can possibly figure out ways to shorten drive times which would then allow more rides to occur which would help maximize future profits. We can subtract the dropoff time from the pickup time to get the drive time which will probably vary by City Type, we can strategically place drivers in areas nearby locations where most pickups occur which will reduce the drive time to pick up, which can be another data type that we can look into add for furture datasets.


    
