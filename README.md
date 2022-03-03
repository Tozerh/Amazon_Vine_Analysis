# Amazon_Vine_Analysis
Module 16 Work

## Project Overview
This project focused on using some basic big data principles to transform and analyze video game review data from the US provided by Amazon. 


## Resources
- Data Source: Amazon's S3-hosted US Video Game Review Data 
- Software/Databases: Amazon Web Service RDS and S3, PySpark, Pandas, SQL (pgAdmin & postgres)

## Results

The results of our video game review analysis are broken out into two categories: paid versus unpaid: 

**Paid Reviews:**
Total number of paid reviews: **25**
Total number of 5-star paid reviews: **9**
Percentage of 5-star paid reviews to total reviews: **36%**

**Unpaid Reviews:**
Total number of unpaid reviews: **8011**
Total number of 5-star unpaid reviews: **2107**
Percentage of 5-star unpaid reviews to total reviews: **26%**

## Summary

The percentage of paid 5-star reviews is significantly higher than unpaid 5-star reviews, which suggests a positivity bias related to the Vine reviewing system. Providing reviewers with free products seems to predispose them to leaving more positive reviews. A big caveat here is the sample size of Vine participants in our data. Unpaid reviews comprise 99.7% of our final dataset, with only .3% of our dataset being made up of paid reviews (i.e. participants in the Vine program). 

In order to expand on our hypothesis that Amazon Vine participants might be predisposed to giving positive reviews, it would be helpful to dive deeper into whether or not a Vine participant actually purchased the product they reviewed. If Vine participants rated a game positively but didn't end up with a verified purchase, it might cast some doubt onto whether or not they actually believed in the positive rating that they gave the game. 
