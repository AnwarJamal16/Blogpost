# Sentiment Analysis of Twitter Data in Python

Sentiment Analysis is the process of analyzing text data and interpret the sentiments behind it and determineswhether a piece of the information is positive, negative, or neutral Sentiment.We fetch 200 live tweets through the Twitter API to perform sentiments analysis.

We follow these three major steps :
	
>Fetching Tweets.

>Categorizing tweets regarding their sentiments (positive, negative or neutral).

>Examining tweets with word cloud and Hashtags.


**1- Create a Developer Account**

First create a developer account and apply for twitter application to get credentials, go to this [Link](https://developer.twitter.com/en/apply-for-access) and get access to a developer account.Once you register, create an app with a suitable name, and wait for the app to approve after that you will have access to Consumer Token, Consumer Secret, Access Key as well as Access Secret these keys will use in step 3 

**2- Install Libraries**

We need to install and import the Twitter packages, to install packages use pip install command.

	pip install tweepy 


**3-Authenticate app using credentials**

add the keys here that you have generated in step 1 in project file 

	consumer_key = 'xxxxxxxxxxxxxxxxxxxx'

	consumer_secret = 'xxxxxxxxxxxxxxxxxxx'

	access_key= 'xxxxxxxxxxxxxxxxxxx'

	access_secret = 'xxxxxxxxxxxxxxxxxxx'


	Read my Blog [post](https://medium.com/@samplecsn16/sentiment-analysis-of-twitter-data-in-python-2f41ba2b3ea5) for detail .

