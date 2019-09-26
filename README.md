# Quora-Question-Pair-Similarity
##### Identifying if two questions are similar, when two questions mean something similar, but have different words
##### Quora is a question-and-answer website where questions are asked, answered, edited, and organized by its community of users
##### in the form of opinions.
##### BOW and TF-IDF are two of the most common methods people use in information retrieval. Generally speaking, SVMs and Naive Bayes 
##### are more common for classification problem, however, because their accuracy is dependent of the training data, Xgboost provided
##### the best accuracy in this particular data set. XGBoost is a gradient boosting framework that has become massively popular, especially
##### in the Kaggle community. Therefore, I decided to use this model as a baseline model, because it is simple to set up, easy to understand
##### and has a reasonable chance of providing decent results. Our baseline model will allow us to get a quick performance benchmark. If we
##### find that the performance it provides is not sufficient, then inspecting what the simple model is struggling with can help us choose 
##### a next approach.

##### The classes are not perfectly balanced, but it is not bad, we are not going to balance them.
##### It can be noticed that we have off a lot work to do in terms of text cleaning. After some inspections, a few tries I took ideas from
###     https://www.kaggle.com/currie32/the-importance-of-cleaning-text

###### Not to remove stop words, because words like “what”, “which” and “how” may have strong signals.
###### Not to stem words.
###### Remove punctuation.
###### Correct typos.
###### Change abbreviations to its original terms.
###### Remove comma between numbers.
###### Change special chars to words. And so on.
