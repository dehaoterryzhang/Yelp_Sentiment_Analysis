# Sentiment Analysis On Yelp Dataset

## Medium Post
Check out my Medium post [here](https://towardsdatascience.com/sentiment-classification-with-logistic-regression-analyzing-yelp-reviews-3981678c3b44?source=friends_link&sk=b9493a3cadf935f4b5c78c1d6c6df25d).

## Table of Content
  * [Kernel](#kernel)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Procedure](#procedure)
  * [Installation](#installation)
  
## Kernel
Check out my Kaggle kernel [here](https://www.kaggle.com/dehaozhang/sentiment-analysis-with-lr).
  
## Overview
I built a sentiment classification model using logistic regression and tried out different strategies to improve upon the simple model. Among those ideas, including bigrams as features has the most improvement in F1 score. For both the simple model and the improved model, I also analyzed its most important textual features.

## Motivation
Sentiment analysis is a highly effective tool for a business to not only take a look at the overall brand perception, but also evaluate customer attitudes and emotions towards a specific product line or service. This data-driven approach can help the business better understand the customers and detect subtle shifts in their opinions in order to meet changing demand.

## Procedure
  * Peek at the Review Data
  * Convert Stars into Categories
  * Decide on Evaluation Metric
  * Text Processing & Vectorization
  * Model Development and Evaluation
  * Visualize Feature Importance
  * Analyze Improvement Strategies
  
## Installation
I did my analysis through Kaggle kernel and I recommended you to do so as well, mostly based on two reasons:
  1. The size of Yelp dataset is quite large but it is pre-loaded through Kaggle kernel so you don't need to download it locally.
  2. Most libraries are already available in this environment so no need to install more libraries locally.
