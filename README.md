# PyBer - Analysis of ride sharing data

Analysis of ride share data with Python, Pandas and Mathplotlib

# Overview

Working as a data analyst for PyBer, a ride sharing company, I was tasked to review driver, ride and fare data and analyze for trends and insights.  The client wishes to determine if there are any suggestions for improved access to services as well as improved affordability for underserved areas. The data was analyzed in Jupyter Notebook using Matplotlib for graphing and analysis. 

# Results

The ride share data identified three different city types: urban, suburban and rural.  The ride and driver data was grouped by each city type to determine if there were differences in the number of rides available in each city type as well as the affordability of those rides. As shown in the table below, the total number of rides and drivers are the most in the urban area and least in the rural areas. Conversely, the average fare per ride and the average fare per driver were the highest in the rural area and the lowest in the urban area.  For both cases, the suburban rates were in the middle between the urban and rural results. 

![PyBerDataFrameSummary](https://user-images.githubusercontent.com/98054953/161443627-be3bf88a-9e91-4f3e-96b6-42f54ba436db.png)

We also looked at pie charts to see what percentage of the total can be attributed to each city type.  The percent of total fares for urban rides accounts for 62.77% of the total revenue.  However, the percentage of drivers in the urban category is 80.9%.  

<img src="https://user-images.githubusercontent.com/98054953/161444119-d6703b44-c54c-4e7c-81ce-23f9813b3cad.png" width="500" height="300"> <img src="https://user-images.githubusercontent.com/98054953/161444122-b9e6ed11-937f-4d9c-beff-2983fd879b20.png" width="500" height="300">

Furthermore, the ride data was plotted over a 4 month period (January to April) by weekly total fares to see if there are temporal trends in the ride data. 

<img src="https://user-images.githubusercontent.com/98054953/161444620-a04059af-58ed-4213-b2b2-d12aaf6b89c6.png" width="700" height="400">


# Summary 

Analysis of the ride sharing data for PyBer indicates there are significant differences in the availabilty and rates for rides depending on the city type location of the rider.  In order to improved accessibility and affordability of the rides to underserved areas, we recommend several steps below. 

1. The riders in the rural areas pay the most for the rides and have the least number of drivers.  PyBer can shift some drivers to the rural and suburban routes where rides are contributing to revenue and have more capacity for drivers to meet the need.  That will reduce the costs to the rural drivers and increase the availabity of drivers in those areas. 
2. The multi-line graph of fares collected over time indicate that the urban rides consistently collects the most fares, followed by the suburban fares and then the rural fares.  There exists some variability in the fares but the lines for each type follow the same general pattern. 
3. Additional data may be helpful to determine if there are any other factors having the majority of the drivers in the urban area when the fares collected are much higher in the rural areas. For example, the ride lengths may be longer in the rural areas which means less income per day for the drivers. 



