## Amazon_Vine_Analysis

# Background

Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:
Deliverable 1: Perform ETL on Amazon Product Reviews
Deliverable 2: Determine Bias of Vine Reviews
Deliverable 3: A Written Report on the Analysis (README.md)

# Results
<img width="732" alt="image" src="https://user-images.githubusercontent.com/6320035/175833505-9645e938-0d1c-440c-aca5-8ce4fc806059.png">

How many Vine reviews and non-Vine reviews were there?
<img width="637" alt="image" src="https://user-images.githubusercontent.com/6320035/175833518-73463e5d-39a3-4ba3-be0e-f8db42377ffb.png">

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
<img width="737" alt="image" src="https://user-images.githubusercontent.com/6320035/175833536-adcee270-f807-47ec-bb19-d583bca047f6.png">

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
<img width="847" alt="image" src="https://user-images.githubusercontent.com/6320035/175833549-bb99968c-77c1-4db3-9ca3-21e8acfbf543.png">

# Summary
From the data above, we can see that most five star reviews are from unpaid is far more than paid five star reviews. 
