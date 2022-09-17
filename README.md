# Amazon_Vine_Analysis
## Overview of the Analysis
In this project, US Digital Ebook Reviews dataset has been selected to perform ETL process to extract, transform the data, connect to AWS RDS instance, and load the transformed data into Postgresql app called PgAdmin.The pyspark has been used to determine the favorable review bias and oerform analysis from the vine members selected in the dataset.

## Results
### How many Vine reviews and non-Vine reviews were there in the dataset?
As it can be seen in the screenshot taken throughout the project, there is no vine reviews, however, there are 65,149 total non-Vine reviews in the dataset.
https://github.com/huzeyfecanbaz/Amazon_Vine_Analysis/blob/c44e9c5642dd96e09e9cf965dbc3c38de554846a/Resources/D-2-1.png

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Because there was no vine review in the selected dataset, the vine reviews could not determined.
- Since all the reviews in our dataset were non-Vine reviews, all the 5 star reviews in our dataset where non-vine reviews and the total was 24,673 5-star reviews.
https://github.com/huzeyfecanbaz/Amazon_Vine_Analysis/blob/c44e9c5642dd96e09e9cf965dbc3c38de554846a/Resources/D-2-2.png

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- As it can be seen in the screenshot below, the percentage of Vine reviews that were 5 stars could not be determined since there was no vine reviews.
- All of the reviews was belong to the Non-vine reviews so that the percentage of the reviews are %37.87
https://github.com/huzeyfecanbaz/Amazon_Vine_Analysis/blob/c44e9c5642dd96e09e9cf965dbc3c38de554846a/Resources/D-2-3.png

## Summary

The dataset that has been analyzed for this project did not have any Vine reviews(paid reviews), therefore, the result of the code was broken from any metrics from the analyzed dataset what percentage of the reviews were from Vine(paid) program participants. On the other hand, all the 5 star reviews were from non-Vine(unpaid) customers and the percentage of 5 star reviews from them were 37.87%. As a result. It is hard to tell whether there are any positivity bias for reviews in the Vine Program from this dataset. To perform any additional analysis on the selected dataset,for sure, there is a need for data from Vine Participants who left a review and from there it can be accurately calculated on percentage of 5 star reviews for Vine Participants to conclude my findings.
