# recommendation_system
Problem Statement

In this project we are trying to build a model that will improve the recommendations given to the users given their past reviews and ratings. In order to do this, I planned to build a sentiment-based product recommendation system, which includes the following tasks:

Data sourcing and sentiment analysis
Building a recommendation system
Improving the recommendations using the sentiment analysis model
Data sourcing and sentiment analysis In this task, I have to analyse product reviews after some text preprocessing steps and build an ML model to get the sentiments corresponding to the users' reviews and ratings for multiple products. The dataset that we are going to use is inspired by Kaggle competition (https://www.kaggle.com/datafiniti/grammar-and-online-product-reviews). The dataset consists of 30,000 reviews for more than 200 different products. The reviews and ratings are given by more than 20,000 users.

The steps to be performed for the first task are given below :

Exploratory data analysis
Data cleaning
Text preprocessing
Feature extraction: In order to extract features from the text data,I choose TF-IDF vectorization.One can use bag-of-words, or word embedding also.
Training a text classification model: I have build at three ML models and analyse the performance of each of these models and choose the best model.
Logistic regression
Random forest
XGBoost
Out of these three models, I select logistic classification model based on its performance.

Building a recommendation system There are following types of recommendation systems.

User-based recommendation system
Item-based recommendation system
User- based recommendation system gives best-suited recommendation system.Now the next step is to recommend 20 products that a user is most likely to purchase based on the ratings. I have used the 'reviews_username' (one of the columns in the dataset) to identify user.

Improving the recommendations using the sentiment analysis model Now, the next task is to link this recommendation system with the sentiment analysis model that was built earlier i.e. Logistic Regression classification model. Now I have 20 products to a particular user using the recommendation engine, I have filtered out the 5 best products based on the sentiments of the 20 recommended product reviews.

In this way, we will get an ML model (for sentiments) and the best-suited recommendation system.

Thank you.
