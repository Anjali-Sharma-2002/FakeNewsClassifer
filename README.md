Dataset link: https://www.kaggle.com/c/fake-news/data?select=train.csv


This project classifies news articles as fake or not using the article's title and author name.
It preprocesses the data first by using Porter stemmer and Tf-idf vectorization. 
Then we use two different models to classify the dataset, namely Logistic Regression and SGD Classifier.
For model evaluation we used "F1 score" on cross validation data (of training data) and test data.


F1 score                |  Cross validation data   |  Test data   |

Logistic Regression     |         0.97             |     0.97     |

SGD Classifier          |         0.98             |     0.98     |
