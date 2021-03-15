# Cryptocurrency News Sentiment Analysis
---

In this analysis, the latest news headlines regarding Bitcoin and Ethereum are used to get a better feel for the current public sentiment around each coin. NLP (Natural Language Processing) is employed here to evaluate the textual sentiments in the news articles. For this analysis, news data and articles on Ethereum and Bitcoin were retrieved from the past 30 days using Newsapi. 

After retrieving the data, data frames of sentiment scores for each coin were created.
Then we used descriptive statistics to answer the following questions:

Q. Which coin had the highest mean positive score?
A. Bitcoin had the highest mean positive score of 0.070053.

Q. Which coin had the highest negative score?
A. Ethereum had the highest negative score of 0.196000.

Q. Which coin had the highest positive score?
A. Ethereum also had the highest positive score of 0.318000. 

## Natural Language Processing
---
Next, used NLTK and Python to tokenize the text for each coin. 

Next, looked at the ngrams and word frequency for each coin.

-Used NLTK to produce the ngrams for N = 2.
-List the top 10 words for each coin.

Finally, generated word clouds for each coin to summarize the news for each coin.

