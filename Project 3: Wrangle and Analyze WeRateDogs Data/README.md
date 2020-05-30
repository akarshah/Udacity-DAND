# Wrangle and Analyze Data - WeRateDogs twitter account

## Project Overview

### Introduction

The dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 6 million followers and has received international media coverage.

This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

The following packages (libraries) need to be installed. 
- pandas
- NumPy
- requests
- tweepy
- json

### Files:
- `wrangle_act.ipynb`: code for gathering, assessing, cleaning, analyzing, and visualizing data
- `wrangle_report.html`: documentation for data wrangling steps: gather, assess, and clean
- `act_report.html`: documentation of analysis and insights into final data
- `twitter_archive_enhanced.csv`: The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets
- `image_predictions.tsv`: a table full of image predictions that classifies breeds of dogs through a Neural Network
- `tweet_json.txt`:  table with retweet count and favorite count gathered from Twitter's API
- `twitter_archive_master.csv`: combined and cleaned data
