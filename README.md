# Machine Learning on Reddit posts

https://docs.google.com/presentation/d/12z8DkTXYmqLhKtCMKcgckLWfRpfoP5nhpWfaPOHrZAc/edit#slide=id.p
# Machine Learning on Reddit posts
https://docs.google.com/presentation/d/12z8DkTXYmqLhKtCMKcgckLWfRpfoP5nhpWfaPOHrZAc/edit#slide=id.p

https://docs.google.com/document/d/1qrT5eE4TLK1bbihS6rBarojNwcUfpxCwA2TtuLNsT0A/edit#

Project 3
6th June 2018
OVERVIEW
Reddit is a social news aggregation, web content rating, and discussion website. Most will already be aware of the currently popularity and importance of Reddit. Reddit being the 6th ranked social media site and 36th ranked site globally. The site is primarily made up of user generated posts whose prominence is determined by recent comments and votes. Given the importance of comments within Reddit, it is essential to understand and predict the factors that make for a popular reddit post.  
GOALS

What characteristics of a post on Reddit are most predictive of the overall interaction on a thread (as measured by number of comments)?
Executives
I have scrapped 2500 posts by API. I became 2350 posts after drop duplications. In the first step, I did some feature analysis. Then I picked up score, title, subreddits and number of comments as my target. 
In order to assess this important question I have assessed a variety of models to determine the best approach to accurately predicting the factors that lead to a popular post (defined as a post with greater than median number of comments). Analysing the data of greatest importance on Reddit I have opted to use a classifier analysis looking at a wide variety of factors. I opted to investigate the effect of titles on the popularity of a post. I then updated my model to gauge the effect of adding several features to our model. I ran these features through several models and tuned the features of each model one by one vs target. Finally, I have picked KNN and Random Forest Classifier to run my model on non-tree and tree model and compare. 
I found a model that accurately predicts the whether or not a post will be popular with ab about  80% accuracy on a consistent basis and approximately 87% rate of correctly predicting positive results. My predictive features (subreddit, score, all title words) were highly effective in other models as well. Ultimately the most effective model selected in our analysis was RandomForestClassifier. My findings suggest that this is a highly effective model which has the potential for further analysis both within the reddit sight. I believe this analysis can also be extended to other post base discussion and social media sites. With the support of General Assembly I believe I can continue to refine our model further for even greater predictive power and to demonstrate that this model will perform well throughout social sites.
