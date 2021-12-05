# Twitter & share prices
## Impact of CEO Tweets on stock prices using Sentiment Analysis

Amalia Temneanu, Dae-Jin Rhee, Marcela Ulloa, Nicolas Bidaux

------

### About The Project

This project was a data challenge for the third week of the Data Science Bootcamp at SIT Academy. 

### Motivation

Is there a basis for the so-called “Elon Effect”?
<!-- ![alt text](https://github.com/NB-01/twitter/blob/master/images/slide1.png?raw=true) -->
Taking some famous tweets from ELon Musk and Jack Dorsey and the Stock Price change for Tesla and Twitter as example, the group proposed this question. 

https://twitter.com/jack/status/1465347002426867720?s=20 (TWTR Stock Price -4%)

https://twitter.com/elonmusk/status/1451015695106560000?s=20 (TSLA Stock Price +5%)

https://twitter.com/elonmusk/status/1457064697782489088?s=20 (TSLA Stock Price -5%)


### Methodology Used

1. Twitter API: Fetching Tweets of company CEOs using Twython.
2. Stock prices of publicly listed companies related to the CEOs (Source: Yahoo finance)
3. Data cleaning
4. TextBlob or VADER for Sentiment Analysis
5. WordCloud
6. Statistical analysis:
    - T-test
    - Correlation matrix: using Pearson correlation coefficient and Spearman correlation coefficient 
    - Simple Linear Regression model
    - Multiple linear regression model

### Preliminary Finds

No correlation found when analysing CEO’s Twitter accounts and their companies’ stock prices evolution.

There is a higher correlation for tweets from Makert influencers in different sectors (commodities, real-estate, etc.).

### Next Steps

Perform statistical analysis a larger amount of data from Market Influencers.

### Contact



### References

https://betterprogramming.pub/detecting-sentiment-from-elon-musks-tweets-using-python-ec7820469ac0
https://towardsdatascience.com/can-we-beat-the-stock-market-using-twitter-ef8465fd12e2
https://towardsdatascience.com/fine-grained-sentiment-analysis-in-python-part-1-2697bb111ed4