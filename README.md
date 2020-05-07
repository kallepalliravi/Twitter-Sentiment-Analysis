# Twitter-Sentiment-Analysis
<b>Date created</b>

4/27/2017

Project Title

Twitter Sentiment Analysis

Project Overview

1. Collect tweets using twitter api using #MOAB using tweepy module
2. Use tweepy.OAuthHandler to create an authentication using the given key and secret
3. Get tweets, use #moab and MOAB, filter out retweets, media and urls for date range 04/13/2017 to 04/15/2017
   append all the tweets to a list.
4. Convert the tweet list to json and save the file. Json data will be in a list tweet_data.
5. create a data frame with the data required for analysis, save the dataframe to a csv file and save the dataframe to a csv file.
6. Using textblob module calulate the sentiment value.
7. Create a column with seniment type for each tweet.
8. create wordcloud from all the tweets to see what are the most used words
9. Export the data to csv file to analyze in R
10. In R, do Hypothesis testing using T-test, within USA and outside USA.
