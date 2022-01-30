# Module_16
### Amazon Reviews ETL

## Overview
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

**Deliverable 1:** Perform ETL on Amazon Product Reviews<br>
**Deliverable 2:** Determine Bias of Vine Reviews<br>
**Deliverable 3:** A Written Report on the Analysis (README.md)

### Deliverable 1: Perform ETL on Amazon Product Reviews<br>

**The Amazon_Reviews_ETL.ipynb file does the following:**

   - An Amazon Review dataset is extracted as a DataFrame
   - The extracted dataset is transformed into four DataFrames with the correct columns 
   - All four DataFrames are loaded into their respective tables in pgAdmin

## Deliverable 2: Determine Bias of Vine Reviews
**The analysis does the following:**

  - There is a DataFrame or table for the vine_table data using one of three methods above 
  - The data is filtered to create a DataFrame or table where there are 20 or more total votes 
  - The data is filtered to create a DataFrame or table where the percentage of helpful_votes is equal to or greater than 50% 
  - The data is filtered to create a DataFrame or table where there is a Vine review 
  - The data is filtered to create a DataFrame or table where there isn’t a Vine review
  - The total number of reviews, the number of 5-star reviews, and the percentage 5-star reviews are calculated for all Vine and non-Vine reviews

## Summary
Deliverable 3: A Written Report<br>

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

- The summary states whether or not there is bias, and the results support this statement
- Additional analysis is recommended 
