# Amazon_Vine_Analysis

## Overview of analysis

The purpose of this analysis was to pull and analyze a dataset about product reviews from Amazon and determine if there is an impact from paid vine reviews.

### High Level Process:
- Pick a dataset
- Transform the data into four separate data frames
- Load the data into a SQL Server
- Analyze the data with PySpark
- Determine if there is any bias toward favorable reviews from Vine members in the dataset

## Results
The dataset that was used in this analysis did not have any Vine reviews, so there did not appear to be any bias in the analysis.

- Total Reviews - 380,604
- Total Five Star Reviews - 227,500
- Percentage of Five Star Reviews from Vine reviewers - 0%
- Percentage of Five Star Reviews from Non-Vine reviewers - 100%

## Summary
Due to there being 0 reviews from Vine reviewers in our dataset, it is safe to say there is no bias in the results of our analysis.

It may make sense to test the analysis on a couple other data sets to see if there is an impact from Vine reviewers. 

I would also recommend a running a probability model on the type of reviewer and the resulting rating.



