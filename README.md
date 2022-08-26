# WeRate Dogs Tweet Analysis- A Udacity Data wrangling focused project

## Introduction

**This act report includes the summary of the Data Analysis process that was taken for the data wrangling project.**

In this project, I worked with three datasets.

Udacity provided the first dataset which is a csv file named twitter_archive_enhanced.csv. It contains basic information about 2356 tweets and was downloaded manually.

The second dataset was a tsv file named image_prediction.tsv which was hosted on udacity server and I programmatically downloaded the file. It contains 2075 predictions made by a neural network that can classify dog breeds.

For the third dataset, I downloaded data collected via the twitter API from my Udacity classroom. This third dataset contains information like the retweet count, favorite count, each tweet recieved for 2327 tweets in the file "tweet_json_text".

## Data Wrangling efforts

While assessing the data, I discovered 14 quality issues and 2 tidiness issues. I used a variety of Pandas methods to clean them up.

## Insights and Findings

Below are some insights and visualizations that I got after I merged the three datasets into a master dataset named master_data.csv.

- The maximum image number is 4, with an average of 1.2, and a minimum of 1.
- The minimum retweet count for the dog tweets is 16, with an average of 2768.4, and the highest retweet count being 79515
- The minimum favourite count for the dog tweets is 81, with an avearge of 8901 favourites per tweet. 
- The highest favourite count recorded is a whooping 132 810.
- 99.6% of the Tweets are in English while, 0.1%, 0.05%, 0.05% are Dutch, Basque, and Estonian respectively.
- The TOP 10 most retweeted and most favorited dog breeds are golden_retriever, labrador_retriever, pembroke, chihuahua, samoyed, french_bulldog, cocker_spaniel, chow, pug, toy_poodle
