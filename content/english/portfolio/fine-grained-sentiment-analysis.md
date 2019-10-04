---
title: Supervised Text Classification for Fine-grained Sentiment Analysis
date: 2018-12-09
image: /img/review-sentiments.png
tags:
    - Natural Language Processing
    - Machine Learning
demo: http://review-sentiments.yjc.me
sourceCode: https://github.com/ktmud/fsauor2018/
---

In response to an AI Competition calling participants to predict sentiment labels for a massive online reviews dataset, I built this repository to test various supervised text classification methods in the context of fine-grained sentiment analysis.

I evaluated the prediction performance, training speed and ease-of-use of more than 6 text feature extraction methods and 9 base classifiers, with the help of scikit-learn's pipeline API. The methods used include TF-IDF, Word2Vec, biLM word embeddings, SVM, Linear Discriminant Analysis, Logistic Regression with Regularization, and Neutral Networks.

I also built a [bespoke interactive visualization](http://review-sentiments.yjc.me/) to facilitate model selection and debugging. It has the capacity to return the predictions for arbitrary review text in real-time and compute overall model performance on the fly.
