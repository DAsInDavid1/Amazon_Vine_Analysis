# Amazon_Vine_Analysis
Using PySpark to perform ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Also using PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset


## Overview of Analysis
The purpose of this analysis was to view the Amazon Vine program service and to test for bias toward favorable reviews from vine members in the dataset of Videogame reviews.

## Results
### Total Reviews
The total amount of vine reviews was 94, and the total amount of normal reviews was 40,471. 
### Total 5-Star Reviews
The total amount of 5-star vine reviews were 48, and total amount of 5-star normal reviews was 15,663
### Percent of 5-Star Reviews
The percentage of 5-star vine reviews was 51.06%, and the percentage of 5-star vine reviews was 38.7%

## Summary
There seems to be some bias for the Vine reviews to be 5-stars more often the normal reviews based off the 38% of normal reviews being 5-star vs the 51% of vine reivews being 5-star. However, I would recommend that more vine reviews be tested since there is not enough vine reviews compared to the normal reviews to come to a complete conclusion.

Another test for bias would be to see the average amount of votes the vine reviews have vs the normal reviews. If the vine reviews are getting more votes, then there may be an indication that the vine reviews are seen more than normal views. Amazon could be showing customers the vine reviews and pushing those ahead of normal reviews which is biased.

