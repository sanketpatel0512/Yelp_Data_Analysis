# Yelp Business Intelligence Data Analysis 
In this project, we will use Yelp datasets from Kaggle that have been hosted on AWS S3 and process them on AWS EMR elastic mapreduce clusters using Python(Pyspark)

### Data
Links to AWS s3 Datasets:

Business Dataset: [s3://yelps3/Yelp_dataset/yelp_academic_dataset_business.json](s3://yelps3/Yelp_dataset/yelp_academic_dataset_business.json)

Review Dataset: [s3://yelps3/Yelp_dataset/yelp_academic_dataset_review.json](s3://yelps3/Yelp_dataset/yelp_academic_dataset_review.json)

Users Dataset: [s3://yelps3/Yelp_dataset/yelp_academic_dataset_user.json](s3://yelps3/Yelp_dataset/yelp_academic_dataset_user.json)

### Cluster & Notebook Configurations


### Analysis

The Yelp_Analysis_NB is the jupyter notebook that analysis the yelp data to answer various business questions

#### Business Questions Answered in Code:

* How many Business Categories are hosted on Yelp?
* How many Businesses are categorised as Active Life?
* Which are the top 20 Business Categories (By Number of Businesses) ?

* Is there any skewness between overall business ratings and ratings by review writers?

* Is there any skewness between overall business ratings and ratings by elite review writers?
