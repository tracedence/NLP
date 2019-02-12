# NLP
Different project on NLP
1.News Headlines Dataset For Sarcasm Detection

Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in these requires the availability of contextual tweets.

To overcome the limitations related to noise in Twitter datasets, this News Headlines dataset for Sarcasm Detection is collected from two news website. TheOnion aims at producing sarcastic versions of current events and we collected all the headlines from News in Brief and News in Photos categories (which are sarcastic). We collect real (and non-sarcastic) news headlines from HuffPost.

This new dataset has following advantages over the existing Twitter datasets:

    Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.

    Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less noise as compared to Twitter datasets.

    Unlike tweets which are replies to other tweets, the news headlines we obtained are self-contained. This would help us in teasing apart the real sarcastic elements.
    
 Content

Each record consists of three attributes:

    is_sarcastic: 1 if the record is sarcastic otherwise 0

    headline: the headline of the news article

    article_link: link to the original news article. Useful in collecting supplementary data


2. Sarcastic or Non-Sarcastic tweet using Natural Language Processing and Text mining Challenge

Build a machine learning model that, given a tweet, can classify it correctly as sarcastic or non-sarcastic. This problem is one of the most interesting problems in Natural Language Processing and Text Mining. 
The prediction has to be made using only the text of the tweet.
Dataset:
One file files is provided as follows
1. sarcasam.csv - This file contains three columns -
○ ID - ID for each tweet
○ tweet - contains the text of the tweet
○ label - the label for the tweet (‘sarcastic’ or ‘non-sarcastic’)
