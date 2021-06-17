# Amazon Vine Analysis

## Overview of the analysis

The purpose of the project is to use PySpark and ETL process to extract data and connect to AWS RDS using PgAdmin Postgres. The data source is from Amazon vine book review data. 
Pandas/Jupyter Notebook will be used to provide detail analytics on vine-table data.  

## Results

PySpark was used to extract the data

![Amazon data](https://user-images.githubusercontent.com/75961117/122311218-b2ef7b00-cedf-11eb-8344-a091ba0cd452.PNG)


Data was subsequently transformed into useful data frames


![review](https://user-images.githubusercontent.com/75961117/122311486-4cb72800-cee0-11eb-8a12-3f7c8d4bec6e.PNG)


![Y filter](https://user-images.githubusercontent.com/75961117/122311597-8daf3c80-cee0-11eb-8510-3dc3eb964083.PNG)

The final data frame analyzed vine_table review by type and categorized the by count and by percentages. We are able to determin the number of 5 star reviews by vine members and non-members. 

![Analysis](https://user-images.githubusercontent.com/75961117/122311717-cf3fe780-cee0-11eb-8552-806f412921df.PNG)

From the analysis, we can answer the following questions.

How many Vine reviews and non-Vine reviews were there?

There was a total of 4 vine reviews and 129477 non-vine reviews.

How many Vine reviews were 5 stars?

Out of the vine reviews, there was 1 five-star review.

How many non-Vine reviews were 5 stars?

74107 of the Non-vine were 5 stars

What percentage of Vine reviews were 5 stars? 

25% of Vine reviews were 5 stars

What percentage of non-Vine reviews were 5 stars?

57.24% of non-Vine reviews were 5 stars.


## Summary: 

There appear to be huge disparity in the review count between vine members and non-vine members which correlate to the 5-star review percentages between the categories. This led us to believe that there is a positivity bias in the Vine program. 





