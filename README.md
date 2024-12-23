ETL Pipeline Using AWS Lambda and S3
Author: Edan Fisher
Inspired By: Sunjana in Data
fhrnmttl@sharklasers.com

This project aims to scrape data on Marvel movies and ingest into an S3 bucket. BeautifulSoup is used to scrape the movies from Wikipedia. The films are then filtered through OMDB database via an API to filter the data into characters per film. This code runs from an AWS Lambda function, with IAM roles setup to ingest into an S3 bucket. 

Inputs:
 - Marvel movies data - scraped from Wikipedia
 - Marvel movies character data - scraped from OMDB

Outputs:
 - The cleaned Marvel movie/character data loaded into S3



