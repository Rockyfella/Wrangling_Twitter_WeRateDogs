# Project: Wrangling and Analyze WeRateDogs Twitter Data

## by Betabasi Daniel

## Introduction
Real-world data is rarely clean. I collected data from various sources and in a variety of formats using Python and its libraries, evaluate its quality and cleanliness, and finally clean it. We call this "data wrangling." In addition to showcasing my data wrangling efforts through analyses and visualizations using Python (and its libraries), I kept track of them in a Jupyter Notebook.

The tweet history of Twitter user [@dog_rates](https://twitter.com/dog_rates), better known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs), is the dataset that I manipulated (analyzed and visualized). WeRateDogs is a Twitter account that assesses users' pets and adds a lighthearted comment. The denominator of these scores is nearly always 10. Nevertheless, the numerators? frequently more than 10. 11/10, 12/10, 13/10, etc. Why? Because ["they're good dogs Brent"](https://knowyourmeme.com/memes/theyre-good-dogs-brent). Over 4 million people follow WeRateDogs, and it has been featured in international media.

WeRateDogs downloaded their Twitter archive and emailed it directly to Udacity so that it could be used for this project. This collection contains all 5000+ of their tweets' basic tweet information (tweet ID, timestamp, content, etc.) as of August 1, 2017.

## Project Steps Overview
My tasks in this project were as follows:
- **Step 1: Gathering data**
- **Step 2: Assessing data**
- **Step 3: Cleaning data**
- **Step 4: Storing data**
- **Step 5: Analyzing, and visualizing data**
- **Step 6: Reporting**


### Step 1: Gathering data
1. I downloaded and uploaded twitter_archive_enhanced.csv and read it into a Pandas DataFrame.
2. I downloaded image_predictions.tsv from the provided URL using the Request library.
3. I queried each tweet's retweet count and favorite ("like") count using the Tweepy library and stored the data in tweet_json.txt
4. I read the tweet_json.txt line by line into a pandas DataFrame with tweet ID, retweet count, and favorite count.
5. I did not include my Twitter API keys, secrets, and tokens in my project submission.

### Step 2: Assessing data
1. I used both visual assessment and programmatic assessment.
2. I included at least eight (8) data quality issues.
3. I included at least two (2) tidiness issues.
4. I documented each issue in a few sentences.

### Step 3: Cleaning data
1. I made a copy of the original data before cleaning.
2. I used the Define-Code-Test framework.
3. I documented the Define-Code-Test framework.
4. I documented each issue in a few sentences.
5. I successfully cleaned all issues identified in the assessing phase.
6. I created a tidy master dataset with all pieces of gathered, cleaned data.

### Step 4: Storing data
I saved the gathered, assessed, and cleaned master dataset(s) to a CSV file named "twitter_archive_master.csv"

### Step 5: Analyzing, and visualizing data
1. I generated at least three (3) separate insights.
2. I produced at least one (1) labeled visualization.
3. I documented the data used to make each analysis and visualization.

### Step 6: Reporting
1. I wrote a report to document the wrangling efforts in a "wrangle_report.html" file.
2. I wrote a report to communicate all the insights and visualizations in an "act_report.html" file.

## Summary of Findings
1. Dogs with the highest number of dog ratings are in pupper dog stage.
2. The average favorite count of the original tweets is twice higher than the average retweet count.
3. The top three most loved breeds of dogs are Golden Retriever, Labrador Retriever and Pembroke.

## Limitations
1. The findings above are based on the records that date back to August 1, 2017 excluding records from recent tweets.
2. An up-to-date tweet archive will help me explore more about the data and draw more insights to update my findings.
3. Emphasis in this project was placed more on the wrangling and cleaning phase hence, the reason for fewer insights.
