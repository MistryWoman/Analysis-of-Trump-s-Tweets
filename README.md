# Analysis-of-Trump-s-Tweets

It's said that on close analysis of Trump's tweets one finds out the non controversial tweets are made from his iPhone ( i.e his staff)
whereas all the controversial tweets are always made from his personal android.

Using text based sentiment analysis we can see that the iPhone and Android texts are clearly written by different people.

His android tweets are angrier and more negative.

The dataset is taken from TwitterAPI.

The sentiment score is determined by using the AFFIN word list made by the Technical University of Denmark. It gives words selcted for sentiment analysis tasks a score from -5 to +5 . This list was made by manual linguistis analysis.

The code here extracts the sentiment score of every token extracted from the tweets by comparing it to the sentiment score given to it by AFFIN.

The words with negative annotations have a higher sentiment score and neutral and positive sentiments have a lower score.



