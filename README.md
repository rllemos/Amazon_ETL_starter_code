# Amazon_ETL_starter_code

# Purpose
To determine if there is a bias towards favorable reviews from Vine members.

# Background
>Project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

>In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

# Overview
* Deliverable 1: Perform ETL on Amazon Product Reviews.

* Deliverable 2: Determine Bias of Vine Reviews.

* Deliverable 3: A Written Report on the Analysis (README.md).

# Results:
# Asks:
### * How many Vine reviews and non-Vine reviews were there?
There was a total of 49  Vine-reviews.
There was a total of 151400 non-Vine reviews.
### * How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were a total of 9 vine reviews with 5 stars and 78061 non-vine reviews were 5 stars.
### * What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Percentage of Vine reviews that were 5 stars is 18%. Percentage of non-Vine reviews that were 5 stars 51%.

# Summary
51% of the reviews in non-Vine program were 5 stars reviews compared to 18% in the Vine program.The difference between these percentages might be do to a negative bias for reviews outside the Vine program. To further grasp what the data is showing it would be best to determine mean,mode,median and standard deviation of both non-Vine and Vine reviews.

