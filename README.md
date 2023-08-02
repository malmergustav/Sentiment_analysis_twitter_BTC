#Sentiment Analysis of Bitcoin Tweets

##Introduction
This project aims to perform sentiment analysis on tweets related to Bitcoin and analyze the correlation between the sentiment of tweets and the price change of Bitcoin. Additionally, we will explore how sentiment varies based on the number of followers of the tweet's author and the location of the tweet.

##Data
The project utilizes two datasets:

Bitcoin_tweets.csv: Contains tweet data related to Bitcoin, including user information, tweet content, and hashtags.

BTC-USD.csv: Contains historical Bitcoin price data.

The sentiment analysis is performed using the VADER (Valence Aware Dictionary and sEntiment Reasoner) tool from NLTK. VADER provides a polarity score for each tweet, indicating its sentiment (positive, negative, or neutral).

##Visualizations
1. Heatmap of Tweet Locations
A heatmap is generated using Folium to visualize the locations of the tweets on a map.

2. Sentiment Score vs. Price Change
A scatter plot is created to show the relationship between the daily average sentiment score and the daily price change of Bitcoin.

3. Sentiment Score vs. Price Change for Users with Many Followers
A scatter plot is created to analyze the sentiment score vs. price change relationship for users with more than 50,000 followers.

4. Sentiment Score vs. Number of Followers
A scatter plot is created to study the relationship between the sentiment score of tweets and the number of followers of the tweet's author.

5. Average Sentiment Score by User Followers
A bar chart is generated to show the average sentiment score of tweets in different user follower bins.

6. Sentiment Score vs. Volume of Bitcoin
A scatter plot is created to analyze the relationship between the sentiment score of tweets and the volume of Bitcoin.

7. Sentiment Score vs. Number of Tweets
A bar chart is generated to show the number of tweets in different sentiment bins.

##Conclusion
This project provides insights into the sentiment of tweets related to Bitcoin and its correlation with Bitcoin's price change. Additionally, it analyzes how sentiment varies based on the number of followers and tweet locations.

Feel free to modify the content or add more details to the Readme file based on your preferences. Remember to replace /path/to/data/files in the "Getting Started" section with the actual path to your data files. If you have any questions or need further assistance, please let me know!
