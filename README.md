# Amazon_Vine_Analysis


##Analysis Overview:

 This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
 The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and  calculate different metrics.
 We focused on the data of US reviews for video games.
"https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz"

##Results:

 Total number of reviews:

 Vine reviews:
 
 ![image](https://user-images.githubusercontent.com/93686963/156961763-e4870a35-2941-4bc8-9ce5-8f8644ae87b2.png)
 
 
 Non-Vine reviews:

![image](https://user-images.githubusercontent.com/93686963/156961814-8fbb2909-1d97-4941-bb95-bb46166ae427.png)


Total number of 5-star reviews:

Vine reviews:

![image](https://user-images.githubusercontent.com/93686963/156962004-5371114a-7b28-482e-9f68-c15949408359.png)

Non-Vine reviews:

![image](https://user-images.githubusercontent.com/93686963/156962068-46ea65de-6e79-420a-ad09-33b47199d409.png)


percentage of 5-star reviews

Vine reviews

![image](https://user-images.githubusercontent.com/93686963/156962170-844da1e0-ee38-4337-b22d-c2b418da53ba.png)

Non-Vine reviews

![image](https://user-images.githubusercontent.com/93686963/156962228-4ddfe1ab-7a78-45a0-aa82-9ef1787b8bca.png)

##Summary:

  51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the       Vine program.
  Additionally we could analyze the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
