# Analysis-of-Trump-s-Tweets

It's said that on close analysis of Trump's tweets one finds out the non controversial tweets are made from his iPhone ( i.e his staff)
whereas all the controversial tweets are always made from his personal android.

Using text based sentiment analysis we can see that the iPhone and Android texts are clearly written by different people.

His android tweets are angrier and more negative.

The dataset is taken from TheTrumpTwitterArchive , which contains over 35,000 tweets, from 2009 to 2018.

Analysis:

[1] Using the time of posts for both the android and iPhone tweets we realize that they have different time stamps ,
indicating that the staff iPhone tweets happen during the afternoon and his personal android tweets happen during the night.

[2] The android tweets were most likely to be copy pasted from other tweets while the iPhone tweets were original content.

[3] The staff created iPhone tweets would always contain photos with links , while android had no photos just angry comments.

[4] Tokenize and remove stopwords using tidytext package

[5] Finding the most common words in tweets made from both devices.

[6] Finding sentiment attached to tweets from both devices.

