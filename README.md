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




