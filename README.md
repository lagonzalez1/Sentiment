# Sentiment
Sentiment analysis on twitter post.
WordCloud image.
This script allows you to input a twitter username and bases on their last 100 tweets show if their tweets have been generally positive or negative.


Sentimenet Analysis: Sentiment analysis is the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information
![image](https://user-images.githubusercontent.com/38986377/171091764-1756c90b-df1b-432e-a9c3-9e52812e8099.png)

Using:
Python
NLTK library
Jupyter
Pandas


Process for WordCloud:
1. Generate an array of objects from twitter API 
2. Each object contains 'text' as a variable containing a tweet.
3. API limits 100 object to be retrived
4. Generating Wordcloud image: 
5. WordCloud generates most commonly used words in a sentance. In our case, we want to generate most common words used within 100 tweets.
6. WordCloud also has methods to eliminate showing 'stopwords', generally these words are remove for natural language processing. Stop words add no meaning to a sentance.
7. Looping through all tweets i generated a long string and feed it into WordCloud function with stopwords as a parameter to generate the image presented.

Process for Sentiment analysis:
1. Using an array filled with tweets as strings
2. NLTK: natural language toolkit allows for strings of sentences to be analyzed. -> polarity_scores() ->  {neu: #,pos: #, neu: #, compound: #}
3. Each tweet is being process and calulated for averages



TO RUN:
replace variable username = "USERNAMEHERE"
git clone 'this'
-python 3.8
-install nltk
-install WordCloud


![example](https://user-images.githubusercontent.com/38986377/171094670-9adbec11-03a9-4790-b89c-6ce5bc0a381b.PNG)

