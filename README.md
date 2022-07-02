# Amazon Vine Analysis - Performing ETL with PySpark

## Overview of the Analysis
The purpose of this project was to help Jennifer analyze reviews written by members of the paid Amazon Vine program to determine if Vine members tend to have a bias toward writing favorable reviews.  For this analysis we used PySpark to perform the ETL process on an Amazon database that held product reviews of automobiles. We then leveraged an AWS RDS pgAdmin database to store the results, after which we returned to PySpark to dig into the data further to determine if there was any bias resulting from the Vine program. 

## Results

**1). How many Vine reviews and non-Vine reviews were there?**
  
  In total there were 82 Vine Reviews in the Automotive dataset and 24,742 non-Vine reviews as seen by the "count" row in each table below.
  
  **Paid**
  
  ![](https://github.com/NRFlood/Amazon-Vine-Analysis/blob/main/Paid.PNG)
  
  **Unpaid**
  
  ![](https://github.com/NRFlood/Amazon-Vine-Analysis/blob/main/Unpaid.PNG)

**2). How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

  In total there were 33 Vine reviews that were 5-stars, and 12,807 non-Vine reviews that were 5 stars.
  
  ![](https://github.com/NRFlood/Amazon-Vine-Analysis/blob/main/5-star.PNG)
  
**3). What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**
  
  As shown in the image above this works out to roughly 40.2% of the Vine reviews being rated as 5 stars, and 51.8% of the non-Vine reviews being rated as 5 stars. 
  
## Summary
As a result of this analysis, it does not appear that there is any positivity bias for reviews in the Vine program when it comes to the automotive industry.  In fact, those that are not part of the Vine program tend to provide 5 star ratings more often (51.8% vs 40.2%) when it comes to this industry.  To further support this conclusion, it would be interesting to run similar analysis on the 4 star rated reviews to determine if the lack of bias within the Vine program appears within those reviews as well.  It would also be worth doing similar analysis on another dataset to see if the same conclusion holds true for reviews within another industry.
       
