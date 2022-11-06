# Amazon_Vine_Analysis

##Overview
The purpose of this project was to analyze reviews written by members that participate on the paid Amazon Vine program. The Vine program is a service that allows sellers to receive reviews of their products. 

## Process
PySpark was used to perform the ETL process, extract the dataset, transform the data and connect to an AWS RDS instance, for which then the transformed data was loaded into pgAdmin. To accomplish this Python PySpark, Pandas, AWS RSD, SQL/PgAdmin and s3 services were used. 

## Data used
[Amazon_data](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Tools_v1_00.tsv.gz) 


##Results


![results](https://github.com/lina2285/Amazon_Vine_Analysis/blob/main/Results.png)


##Summary
The data shows that more than half (57%) of the reviews have 5 star reviews for those who are part of the paid Vine program. For those that are not part of the paid Vine program, the 5 star revies are slightly less than half (46%). Comparing the percentages we can see there is a positive bias for those with the paid Vine program; however, the total reviews with the paid Vine program are only 285, where the unpaid are 31545, this shows, that eventhough percentage-wise, the bias goes towards paid, there are a lot more reviews for the unpaid version, which skus the result. 
