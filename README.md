# Movies_ETL

Overview

This project provides a clean set of data for an upcoming hackathon sponsored by Amazing Prime Video. We created an automated ETL pipeline for various large datasets from Kaggle, Movielens, and Wikipedia. We use Python and Pandas for our data-wrangling and then PostgresSQL to store finished data for the participants to use for the event.


Process
Initially, we investigated our datasets to see what we were dealing with and began to devise a plan. 

	A brief summary of steps taken:
* Make copy of data
   * This allows us to protect the original data and to retrace our steps in case of a mistake
* Filter data using various methods including list comprehension
* Decide what to keep and what to exclude
* Create functions to clean data 
* Combine multiple data sources and send to SQL


Summary

We took messy and almost unusable data, carefully combed through it and transformed it, and then pushed the final set into a SQL database for our contestants to use during the hackathon. Now the hackathon has a reliable, clean dataset ready for analysis.


