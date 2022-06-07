# Amazon Vine Analysis

## Overview
In this project, there will be access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. One of these datasets will be used for PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then I will use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results
### Vine Reviews
- Total: 94
- 5-Star Reviews: 28
- 5-Star percentage: 51.1%
![1](https://github.com/Jandreezy/Amazon_Vine_Analysis/blob/main/Images/vinedf.png?raw=true)
### Non-Vine Reviews
- Total: 40471
- 5-Star Reviews: 15663
- 5-Star percentage: 38.7%
![2](https://github.com/Jandreezy/Amazon_Vine_Analysis/blob/main/Images/nonvine.png?raw=true)

## Summary
Based on the data, there seems to be little to no bias towards vine users. Even though the amount of non-vine users is hugely different to the amount of vine users, the difference in 5-star percentage is only about 12%. That isn't enough of a variance to conclude that there is a bias according to the dataset that was given.