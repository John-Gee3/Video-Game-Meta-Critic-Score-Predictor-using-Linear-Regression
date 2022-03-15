# Video Game MetaCritic Score Predictor using Linear Regression
In this script we attempt to predict video game MetaCritic scores based on genre, publisher, user reviews, platform and rating. 

Data review does show some interesting data (such as Valve being completely outside of the algorithms predictions, not surprising given the quality of their games), along with a feature break down of what the model found to be the features that would lead to the highest metacritic store. Script will save the data in csv and png files for review, and further process

Data from kaggle (https://www.kaggle.com/xcherry/games-of-all-time-from-metacritic), cleaned, labels encoded and then a linear regression model from sklearn was trained on the data. Ultimately the accuracy shows linear regression with this data set does not do well predicting the MetaCritic score. The argument can be made that review scores can be very subjective, and the features we are using cannot accurately predict how a game will be received. Nonetheless, it was a fun example of trying to use machine learning to create a predictive model

![chart1](score_genre.png)
