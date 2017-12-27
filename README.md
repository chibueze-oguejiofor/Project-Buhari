# Project-Buhari

This project aims at observing the sentiments of twitter users in Nigeria. The timing for the collection of these tweets come at a very delicate time (27th December 2017) when the fuel scarcity which lasted almost 7 days slightly subsided.
The goal is to obbserve if Nigerians blam the incumbent president for the fuel scarcity or not:

1. Script.py gathers tweets up to 7 days back. A total of roughly about 10,000 tweets/comments were collected excluding retweets in JSON.
2. Project-Buhari.ipynb saves the tweets as texts, cleans the tweets to remove links and non alphanumeric characters and savesd to a pandas dataframe.
3. Sentiment analysis was carried out on the clean tweets and are classified as 'POSITIVE','NEGATIVE' or 'NEUTRAL'
