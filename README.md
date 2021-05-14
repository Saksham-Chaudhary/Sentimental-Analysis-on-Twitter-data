# Sentimental-Analysis-on-Twitter-data
What is Sentimental Analysis?
Sentimental Analysis is a Natural Language processing technique used to determine whether the data is positive, negative or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.


Tools and Languages:
The language used is Python and tool is Jupyter Notebook.
Some of the libraries used: Pandas, numpy, tweepy, matplotlib, seaborn etc.


Methodology Followed: 

1)Importing the libraries:
 

2)Loading the Dataset:
We have a labelled dataset of 31962 tweets. The dataset is in the form of a csv file with each line storing a tweet id, its label and the tweet.

 
3)Pre-processing  the Dataset:
The dataset contains @usernames, hashtags, numbers and many more, so we will need to preprocess the dataset and remove all unwanted information.
 

4)Exploratory data analysis:
We will add the tweet’s subjectivity and polarity to the dataframe. I created two functions to find the subjectivity which is how subjective or opinionated the tweet is, the score of 0 is a fact and score of 1 is an opinion, the other one to find the polarity which is how positive or negative is the text, the score of -1 is high negative, the score of 0 is neutral and the score of +1 is positive.
 

Visualizing the frequent words:

Extracting Hashtags:
  
Plotting Graph:
 
Model Training and Accuracy:
 

