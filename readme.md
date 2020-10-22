# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) GA DSI Capstone Project

## Restaurant Recommendation System based on Yelp Reviews Dataset

## Overview

This Capstone Project will apply Natural Language Processing on Yelp Restaurant Reviews in order to create new insights and features that can be used for the various Recommendation System Models.

Using Sentiment Analysis Packages like Textblob and VADER, we can analyze text reviews to derive further quantitative metrics on a user's overall sentiment and review of a restaurant visit. Combining sentiment scores with rating scores from reviews, we hope to build out a super score that better reflects a user's overall experience and feeling towards a restaurant. This super score will be used in our Collaborative Filtering Recommendation System.

Furthermore, this project will also incorporate Topic Modelling (LDA) to further classify text reviews based on several dominant topics. By identfying common key words in different dominant topics, we will use these key words in our Content Based Recommendation System.

Lastly, this project will use the longitude and latitude points of restaurants to build a Location Based Recommendation System and cluster restaurants together using the K-Means Clustering Algorithm.

## Problem Statement

Given the recent impact of Covid-19, many people have decreased their visits to restaurants in order to comply with the social distancing orders from governments. As such, many people have turned to online food delivery services to satisfy their cravings and meals on a daily basis. However, many lesser known restaurants have suffered during this period due to the lack of customers and online orders especially if food delivery apps are consistently recommending other restaurants to their normal customers.

While many delivery apps recommend users restaurants based on their location proximity, what this Capstone Project aims to create is an alternative food recommendation system based on user reviews and sentiment analysis. As more and more people are starting to frequent restaurants again in Phase 2, this Capstone Project aims to help people become more aware of local Restaurants through this Recommendation System and help keep their businesses alive.

The Recommendation System Models will be built based on the Yelp Reviews Dataset on Kaggle, particularly focusing on Restaurant Reviews in the city of Toronto. With the models built out, this project can be applied to other cities as long as we can get similar datasets for such cities.

## Datasets and Data Dictionary

The Dataset used for this Capstone Project comes from the Kaggle Yelp Dataset Challenge at: https://www.kaggle.com/yelp-dataset/yelp-dataset

Data Dictionary for Yelp Reviews Dataset:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|business_id|object|Yelp Reviews|Unique ID Key for each Restaurant|
|user_id|object|Yelp Reviews|Unique ID Key for each Yelp User|
|stars|int64|Yelp Reviews|User Review Rating Score|
|text|string|Yelp Reviews|Text Reviews of Restaurants|
|date|object|Yelp Reviews||Date and Time of Review|
|word_count|int64|Yelp Reviews|Word Count for each Review|
|cleaned_text|string|Yelp Reviews|Cleaned Text Reviews after Text Processing|
|polarity|float64|Yelp Reviews|Polarity Sentiment Score of Reviews|
|subjectivity|float64|Yelp Reviews|Subjectivity Sentiment Score of Reviews|
|compound|float64|Yelp Reviews|VADER Compound Score of Reviews|

## Key Concepts and Tools used

1. Natural Language Processing
2. Textblob Sentiment Analysis
3. VADER Sentiment Analysis
4. Topic Modelling (LDA)
5. Location-Based Recommendation System
6. K-Means Clustering Algorithm
7. Collaborative-Filtering Recommendation System
8. Truncated Singular Value Decomposition
9. Cosine Similarity
10. Content-Based Recommendation System
11. CountVectorizer

## Contents:

1. Part One: Data Importing and Cleaning
2. Part Two: EDA and Sentiment Analysis
3. Part Three: Topic Modelling
4. Part Four: Recommendation Systems

## Conclusion and Limitations

This Capstone Project seeks to create a few Recommendation System Models to recommend users different restaurant options during this period where the world is currently facing a pandemic. Nevertheless, more reviews and data would improve the accuracy of our models and as a result, improve the suggestions made by our Recommendation Systems.

In terms of what can be done to improve these models in the future:

1. Account for Bi-Grams and Tri-Grams during our Natural Language Processing Stage to generate better Sentiment Analysis Scores and Topic Modelling outcomes.

2. Incorporate Neural Network and Deep Learning Concepts into our collaborative filtering recommendation system.

3. Incorporate the concept of Graph Theory to optimize travelling and delivery routes for our location-based recommendation system.
