# sentiment analysis on restraurant reviews

The purpose of this analysis is to build a prediction model to predict whether a review on the restaurant is positive or
negative. To do so, we will work on Restaurant Review dataset, we will load it into predicitve algorithms Multinomial
Naive Bayes, Bernoulli Naive Bayes and Logistic Regression. In the end, we hope to find a "best" model for predicting
the review’s sentiment.
Natural language processing (NLP) is an area of computer science and artificial intelligence concerned with the
interactions between computers and human (natural) languages, in particular how to program computers to process and
analyze large amounts of natural language data. It is the branch of machine learning which is about analyzing any text
and handling predictive analysis.
Sites such as Zomato have a star rating system that lets users easily see what the general opinion about a particular
establishment is without having to read all the reviews for that particular restaurant. However, there is an abundance of
user generated information online from social media platforms like twitter, facebook or blog posts where users express
their sentiment about a particular product or business. Since the reviews data on the Yelp dataset provides both the star
rating and the text for each review, I wanted to know if it would be possible to train a machine learning model with this
data in order to identify if a particular business review was positive or negative based only on its text.
A Naive Bayes algorithm was used to build a binary classification model that would predict if the review’s sentiment
was positive or negative. A Naive Bayes classifier assumes that the value of a particular feature is independent of the
value of any other feature, given the class variable. It uses the training data to calculate a probability of each outcome
based on the features. One important characteristic of the Naive Bayes algorithm is that it makes naive assumptions
about the data. It assumes that all the features in the dataset are independent and equally important.
