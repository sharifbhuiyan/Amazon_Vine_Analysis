## **<h1 align="justify"> Amazon_Vine_Analysis**
  	
---
## Overview of the project: 
<p align="justify">The objective of the project to analysis Amazon Vine program and to determine if there is any bias toward favorable reviews from Vine members in dataset. To furnishs the project analysis, Pyspark is used for ETL, AWS-RDS is used for storage data, and pull data from AWS-RDS to pgAdmin for query rquirement.
 <p>
	
	
---

<p align="justify">This project consists of three technical analysis deliverables. <p>

- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)

	

### Resources
- Data Source: [  Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Video Games Review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)  	
- Software: AWS(S3, RDS) ; PostgreSQL_11, pgAdmin 4, Google Colab Notebook 

## Results: 
### Total number of reviews:

- Vine and Non-Vine reviews:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Amazon_Vine_Analysis/blob/main/Resources/paid%20total%20number%20of%20reviews.png
</p>  
	

	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Amazon_Vine_Analysis/blob/main/Resources/unpaid%20total%20number%20of%20reviews.png
</p>  
	
### Total number of 5-star reviews :
- Vine and Non-Vine reviews:
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Amazon_Vine_Analysis/blob/main/Resources/paid%205-star%20reviews.png
</p>  

	

<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Amazon_Vine_Analysis/blob/main/Resources/unpaid%205-star%20reviews.png
</p>
	
### Percentage of 5-star reviews :	
- Vine and Non-Vine reviews:
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Amazon_Vine_Analysis/blob/main/Resources/paid%205-star%20reviews%20percentage.png 
</p>
	


	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Amazon_Vine_Analysis/blob/main/Resources/unpaid%205-star%20reviews%20percentage.png
</p>

	


