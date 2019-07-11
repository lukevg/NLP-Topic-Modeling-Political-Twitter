# NLP-Topic-Modeling-Political-Twitter
NLP Topic Modeling Political Twitter

For this This NLP project I created a TweePy program to gather tweets that were to, from, or retweets of accounts belonging to American governors, congress members, and executive branch members (including the president) over a seven-day stretch in May 2019 for the purpose of modeling the most distinct and popular topics during that time period. 

Tweets were entered into a MongoDB database and were cleaned, tokenized, and lemmatized using Python's NLTK library. I then created LSA, NMF, and LDA topic models, using both a count vectorizer and TF-IDF vectorizer on each model type, and ran many iterations of these models as I continually added more stop words and adjust the minimum and maximum thresholds for word frequency to try to get distinct topics.

While none of these models were able to get a large number of distinct topics, this project shows the overwhelming influence the president's account has over the political discourse on Twitter. The notebook includes code used for gathering the tweets, preparing the text for modeling, and for creating the topic models. The PowerPoint slides summarize the process and findings, and a blog post in my blog repo further expands upon the slides.
