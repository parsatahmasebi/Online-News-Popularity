# Online-News-Popularity

The growth of the internet and technology has contributed to the popularity of online news articles and blogs. While print news is not completely dead yet, a growing number of people prefer to search the web for the day’s happenings, as online news is free, immediate, and convenient. In fact, in 2018 Pew Research noted that just over 50% of Americans get their news from some online format.  According to Forbes, the number had increased to 55% in 2019.

Our team used data on Mashable articles from a two-year period to build a few machine learning models that predict the popularity of an article given a set of features about that article, such as the number of words in the article, the day of the week the article was published on, and the average sentiment polarity of the article content. In order to run these models, we discretized the continuous prediction variable “shares” into two categories: “High” popularity for those articles with a number of shares greater than or equal to the median number of shares for all articles, and “Low” popularity for those articles with a number of shares less than the median number of shares for all articles.

In order to predict the popularity of a given article, we built three machine learning models using Naïve Bayes, Random Forest, and K-Nearest Neighbors (KNN) algorithms. Among these models, Random forest performed the best by having around 65% accuracy on the training dataset. 

The goal of this project was to examine the effect that each step of preproccesing may have on the accuracy of these models, so we developed each of them before and after data preprocessing steps.




