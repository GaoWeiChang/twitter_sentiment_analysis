# Twitter Sentiment Analysis
## Overview
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This project we will analyzing text data from social media platforms Twitter by using a dataset from the HuggingFace(https://huggingface.co/datasets/carblacac/twitter-sentiment-analysis), to understanding the customer experiences. By applying machine learning techniques to text data, we can extract subjective information and classify it as positive and negative. This analysis can help businesses and organizations make informed decisions by providing insights into consumer behavior and trends.

## Problem
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; With the vast amount of data generated on social media platforms every day, it's challenging for businesses to manually sift through comments, tweets, and posts to discern general sentiments about their products, services, or brand. Automating this process through sentiment analysis not only saves time and resources but also provides a more objective and comprehensive analysis of public sentiment

## Objective
- **Data Cleaning** : handling the sentiment text to lowercase and drop unnecessary columns.
- **Split dataset** : split the SentimentText and label into training/testing set.
- **Feature extraction** : turn text into vector by tf-idf for machine learning task.
- **Model Training** : using classifier algorithm to train a model such as SVM, Naive-Bayes and Logistic Regression.
- **Model Evaluation** : The effectiveness of the model will be evaluated based on its **accuracy**, **precision** and **recall**.

## Dataset Description
| __Variable__ | __Description__ |
|     :---      |       :---      |      
| ItemID | Indicating the item's ID. |
| Sentiment | The user's feeling, 0 indicates the sentence has a negative sentiment, while 1 indicates a positive feeling. |
| SentimentSource | The anonymous user. |
| SentimentText | Indicate a sentence (or tweet). |
