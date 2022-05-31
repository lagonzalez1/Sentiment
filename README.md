# Sentiment analysis


This scrip analyizes the last 100 tweets from a user and displayes sentiment on the entire data set. Also generates an image using wordcloud for commonly used words.

Sentimenet Analysis: Sentiment analysis is the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information
![image](https://user-images.githubusercontent.com/38986377/171091764-1756c90b-df1b-432e-a9c3-9e52812e8099.png)

Dependancies:
Python,
NLTK library,
Jupyter,
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



TO RUN: \n
replace variable username = "USERNAMEHERE" \n
git clone 'this' \n
-python 3.8 \n
-install nltk \n
-install WordCloud \n

Example: 

![example](https://user-images.githubusercontent.com/38986377/171094670-9adbec11-03a9-4790-b89c-6ce5bc0a381b.PNG)

![output1](https://user-images.githubusercontent.com/38986377/171095113-46d038cb-fa77-430a-967f-bd31cc4e8a5e.PNG)

![output2](https://user-images.githubusercontent.com/38986377/171095119-1c1510fe-8f04-41c1-89b7-a38a81d86aab.PNG)

