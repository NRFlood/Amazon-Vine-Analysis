# Amazon VineAnalysis - Performing ETL with PySpark

## Overview of the Analysis
The purpose of project was to help Jennifer analyze reviews written by members of the paid Amazon Vine program to determine if Vine members tend to have a bias toward writing favorable reviews.  For this analysis we used PySpark to perform the ETL process on an Amazon database that held product reviews of automobiles. We then leveraged an AWS RDS pgAdmin database to store the results, after which we returned to PySpark to dig into the data further to determine if their was any bias resulting from the Vine program. 

## Results

**1). How many Vine reviews and non-Vine reviews were there?**
  
  In total there were 82 Vine Reviews in the Automotive dataset and 24,742 non-Vine reviews.
  
  ![](https://github.com/NRFlood/Amazon-Vine-Analysis/blob/main/Paid.PNG)
  
  ![](https://github.com/NRFlood/Amazon-Vine-Analysis/blob/main/Unpaid.PNG)

**2). How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

  In total there were 33 Vine reviews that were 5-stars, and 12,807 non-Vine reviews that were 5 stars.
  
  ![](https://github.com/NRFlood/Amazon-Vine-Analysis/blob/main/5-star.PNG)
