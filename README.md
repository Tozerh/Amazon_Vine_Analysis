# Amazon_Vine_Analysis
Module 16 Work

## Project Overview
This project focused on using some basic big data principles to transform and analyze video game review data from the US provided by Amazon. 


## Resources
- Data Source: Amazon's S3-hosted US Video Game Review Data 
- Software/Databases: Amazon Web Service RDS and S3, PySpark, Pandas, SQL (pgAdmin & postgres)

## Results

The results of our video game review analysis are broken out into two categories: paid versus unpaid: 

Paid Reviews: 
Total number of paid reviews: 25
Total number of 5-star paid reviews: 9
Percentage of 5-star paid reviews to total reviews: 36%



![PyBer Summary](https://github.com/Tozerh/PyBer_Analysis/blob/main/PyBer%20Summary.PNG)

The PyBer data summary above provides some key details on the differences between ride share usage in the different city types we explored: urban, suburban, and rural:

- *Urban riders tend to take more rides than any other city type, but also pay less per ride based on average fare.* 

![Riders by Type](https://github.com/Tozerh/PyBer_Analysis/blob/main/Resources/total_rides_by_type.png)

Coupled with the pie chart above, the data in the summary data frame point to a couple of options for PyBer: We could increase premiums for urban riders in order to boost revenues and/or we could consider lowering costs for rural riders to increase uptake of PyBer's services, which should result in long-term profitability for this sector of PyBer's business. 

- *Average Fare per Driver is highest in the Rural city type.* According to the summary data frame above, drivers in rural areas may be taking longer trips, resulting in a higher fare for each ride. Given that rural areas are definitionally more spread out than urban or suburban areas, this thesis does track with our data. It is also possible that PyBer is increasing premiums for rural riders in order to incentivize drivers to actually use PyBer as an income source. The more drivers PyBer can deploy in rural settings, the higher rural customer's satisfaction scores should be (E.g., more PyBer drivers in rurual areas will make it easier for rural riders to call a PyBer, PyBers will become less expensive and a better value, etc.). 

- *There are many more drivers in cities than in other settings.* 

![Driver by Type](https://github.com/Tozerh/PyBer_Analysis/blob/main/Resources/total_drivers_by_type.png)

The data show that there are just under five times more drivers in urban settings than suburban settings and almost thirty-one times more drivers in urban settings than rural. This data suggests that urban drivers are more likely to pick up a few trips here and there, with fewer urban drivers relying on PyBer as a main driver for their income. 

- *Urban centers are currently the largest profit center for PyBer.* 

![Fare % by Type](https://github.com/Tozerh/PyBer_Analysis/blob/main/Resources/total_fares_by_type.png)

Urban riders account for 62.7% of all of PyBer's fares in this data set and are foundational to PyBer's success. 

## Business Recommendations

1) In suburban and rural areas PyBer should focus on increasing the number of drivers to service its customer base. The average rides-to-driver ratio in rural and suburban areas is 1.44, indicating that there is more demand than supply. PyBer could make inroads into improving its satisfaction scores from customers by incentivizing more people to become PyBer drivers in suburban and rural settings.

2) Parallel to the first recommendation above, Pyber might also give riders incentives and discounts to encourage more rides in suburban and rural settings to increase revenue in these areas. The demand seems to be there, and discounts and deals might be a nice catalyst to an increased uptake of PyBer's services in these areas. 

3) Given that there are many more riders than drivers in urban areas, there may be some slack that can be picked up in terms of incetivizing more rides. PyBer might consider selling packages of rides that expire each week to ensure that customers continue to use their services. Urban settings are very competitive in terms of transportation options, and PyBer should do everything that it can to ensure repeat customers on their platform. 
