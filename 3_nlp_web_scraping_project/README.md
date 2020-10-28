# Project 3: Web APIs & Classification

### Gladys Pao, SG-DSI-17

## Problem Statement

Due to reddit's high popularity among smartphone users in the United States (U.S.), we have been hired by LG to analyse posts from two subreddits (LG's mobile OS, <b>/r/Android</b>, and its direct competitor, <b>/r/Apple</b>) and get insights on how to improve their marketing efforts and their products so as to increase their market share in the U.S. smartphone industry. Working with Reddit's API to scrape and store user posts between these two subreddits, we will make use of Natural Language Processing to analyse, understand and derive information from text data before training a subreddit post classifier through the selection of an appropriate classification model. This will in turn allow us to classify and predict which subreddit a given post come from. To choose our final classification model, we will be comparing the models' accuracy scores (and specificity and recall rates if there are two or more models that performed similarly in accuracy).

Ultimately, we aim to provide a model that can accurately predict a post's subreddit origin, highlighting not only the most popular words but also the most indicative words (which suggests the subreddit origin of a post) in each subreddit. Through the model, we can analyse, gain useful insights and provide powerful recommendations for LG in their marketing (and product development) efforts, hence helping the brand continue to grow their market share in the U.S., among the other big players like Apple, Samsung and Google in the smartphone industry.

## Executive Summary

With reddit's high popularity in the United States (U.S.), this project that deals with web APIs, Natural Language Processing (NLP) and Classification has been initiated by established smartphone brand LG for their own marketing (and product development) purposes. With the aim of improving the brand's market share in the U.S. smartphone industry, we are tasked to work with Reddit's API to scrape and store user posts from two subreddits, /r/Apple and /r/Android, and eventually train a classifier model that can accurately predict a post's subreddit origin and help gain insights on popular and important words from each subreddit.

An appropriate classification model (TfidfVectorized Multinomial Naive Bayes) for the prediction of subreddit origin was chosen after comparing largely based on their accuracy scores (with further comparison done based on its recall and specificity rates, and eventually with its RUC-AOC score). Finally, we studied and interpreted the classification model, checking for important words from each subreddit that can definitively indicate the subreddit origin of a post.

Through exploratory data analysis and the study of each subreddit's most important words, it appears that highly popular words from each subreddit are usually product-related or feature-related. However, initial exploratory data analysis also included some highly-ranked emotionally-driven words while analysis of important words after modelling showed otherwise. This lack of emotionally-driven words does correspond to our sentiment analysis that we have done after studying the polarity of words and its frequency distribution from both subreddits, in which the nature of both subreddits lean more towads neutral sentiments.

This is followed by recommendations for increasing LG's market share in the U.S. smartphone industry:

- Continue to invest and engage in more R&D to develop smartphones that can solve the painpoints of customers <br>
- Slightly tweaking the direction of their marketing campaigns to highlight how their products can help to solve many current pain points of their target consumers<br>
- Engage in influencer marketing due to the high popularity of smartphone reviews <br>
- Improve and maintain good quality in-store and support experience<br>
- Expand the LG forum page to not only include US and Canada regions, but also worldwide to facilitate more discussions on these forums.

Moving forward, the model can be trained with more new text data from both subreddits repeatedly, so that the model can continuously calibrate and improve its accuracy overtime. Besides that, LG can also choose to invest in more market research to learn more about their target consumers outside of reddit, since subreddit users are only a proportion of LG's target consumers in the United States. In addition, videos or news articles linked in the subreddit posts can also include valuable information regarding their target consumers and should be studied too.

### Contents:
- Executive Summary
- Problem Statement
- Data Collection
- Data Cleaning
- Some Preprocessing with Exploratory Data Analysis
- Distributions
- Modelling
- Selection and Evaluation of Model
- Our Final Model
- Conclusion and Recommendations
- References

## Overview of Data
The following links contain the sources of data for this project:<br>
/r/Apple: https://www.reddit.com/r/apple<br>
/r/Android: https://www.reddit.com/r/android

## Conclusion and Recommendations
### Recommendations
To improve LG's market share in the U.S. smartphone industry, the following recommendations can be considered:
1. Invest and engage in more R&D, so that LG products/smartphones can solve the painpoints of customers with regards to the usage of smartphones. <br>
2. Slightly tweak the direction of LG's marketing campaigns, since the direction of most LG commercials seem to be gearing more towards advertising how their new technology can help 'enrich' their lives as opposed to solving their current problems. Hence, the new direction of their new marketing campaigns should be geared towards how their smartphones helps to solve their target consumers' painpoints.<br>
3. Engage in influencer marketing, since reviews from influencers are very popular among both subreddit users, who are the target consumers of LG. The engagement of key opinions leaders (such as very highly-followed reviewers from YouTube and reviews sites) can definitely help to gain some traction and hype for their new product releases. <br>
4. Improve and maintain good quality in-store and support experience, since in-store and support experience seems to be a gripe of various smartphone users. <br>
5. Expand the LG forum page to not only include US and Canada regions, but also worldwide since online platforms that allow product-related discussions are very popular among LG's target market and worldwide discussions of LG products will help to facilitate further discussions on these forums.<br>

### Conclusion
After comparing the performance of all models, we have decided to choose a TfidfVectorized Multinomial Naive Bayes (TF-MNB) model for our subreddit post classifer due to its high accuracy rate (together with its high recall, specificity rates and eventually with its high RUC-AOC score). Through exploratory data analysis and the study of our most important words as generated by our chosen model TF-MNB, we have found out that the highly popular words from each subreddit are usually product-related or feature-related. However, initial exploratory data analysis had some emotionally-driven words being ranked highly while analysis of important words after modelling showed otherwise. This definitely translates to more neutral sentiments for both subreddits, which was what we have gathered after polarity sentiment analysis of both subreddits. With the usage of this classifer as well as the knowledge of important words for each subreddit, LG can make use of these insights to further improve their products, service and marketing efforts to eventually improve their smartphone market share in the United States.

Moving forward, the model should be fed with more new text data from both subreddits repeatedly, so that the model can continuously calibrate and improve their accuracy overtime. Besides that, LG should also choose to invest in more market research to learn more about their target consumers outside of reddit, since subreddit users are only a proportion of LG's target consumers in the United States. In addition, videos or news articles linked in the subreddit posts can include valuable information regarding their target consumers and should also be studied in the future.
