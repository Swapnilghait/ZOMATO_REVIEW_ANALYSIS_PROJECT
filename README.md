# Zomato Reviews Sentiment Analysis Project
Welcome to the Zomato Reviews Sentiment Analysis project! This venture delves deep into the world of Zomato reviews for a specific restaurant, employing Natural Language Processing (NLP) and machine learning to decipher sentiments expressed by patrons. Here's a detailed breakdown of our journey:


Project Overview

Objective

The primary goal of this project is to develop a robust machine learning model capable of accurately classifying Zomato reviews as either positive or negative based on a meticulously curated dataset comprising 1000 reviews.


Tools and Technologies

Programming Language: Python

Libraries: pandas, nltk, scikit-learn

Algorithm: Naive Bayes


Project Steps

1. Importing Libraries
We initiated the project by importing essential Python libraries to equip ourselves for data manipulation, NLP, and machine learning tasks.

2. Importing Dataset
Our dataset, a treasure trove of Zomato reviews, was meticulously collected and imported. Key columns, such as 'Review Text' and 'Sentiment,' were identified for subsequent analysis.

3. Cleaning the Dataset
Ensuring data quality is paramount. To achieve this, we executed a comprehensive data cleaning process:

Removed irrelevant columns to streamline our dataset.
Addressed missing values to prevent any anomalies.
Eliminated duplicate entries for data integrity.
Engaged in text preprocessing:
Converted text to lowercase for uniformity.
Removed special characters to focus on the essence of the reviews.
Handled stopwords to extract meaningful insights.


4. Bag of Words Creation
The Bag of Words model played a pivotal role in transforming our textual data into a numerical format amenable to machine learning algorithms:

Tokenization broke down the reviews into individual words.
Created a matrix where rows represented reviews, columns represented unique words, and values indicated word frequencies.


5. Splitting Data into Test and Training Sets
To ensure the model's robustness, we split the dataset into distinct training and testing sets. This strategic division facilitated effective model training and accurate evaluation.


6. Training Naive Bayes
The Naive Bayes algorithm, celebrated for its effectiveness in text classification, was selected for training our model. This phase involved exposing the algorithm to the training dataset to learn and discern sentiments.


7. Prediction on the Test Set
With the model finely tuned, we set it loose on the test set to predict sentiments, allowing us to gauge its predictive prowess.


8. Making Confusion Matrix
A comprehensive analysis is incomplete without a scrutiny of the confusion matrix. We meticulously evaluated the model's performance, examining true positives, true negatives, false positives, and false negatives.
