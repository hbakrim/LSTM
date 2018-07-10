# LSTM
Long short-term memory model (LSTM)

This notebook attempts to tackle a classification problem by using Long short-term memory model (LSTM). We choose to take a kaggle challenge as best use case for this algorithm. We'll use two differente API to implement this algorithm: tensorlow and Keras


## Data Description

A large number of Wikipedia comments are provided which have been labeled by human raters for toxic behavior.  The problem has only one predictor variable, 'comment_text', which is to be labeled or classified with respect to six target variables.

The target variables are the following types of toxicity:

    • toxic • severe_toxic • obscene • threat • insult • identity_hate

The training set consists of labeled 159,571 comments (observations) and the test set consists of 153,164 comments to be labeled.

The goal of this competition is to create a model which predicts a probability of each type of toxicity for each comment.

The data has been made available via the following url - https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data



## Problem Statement

Determine the probability of different types of toxicity of comments from Wikipedia edits.

This is a multi-label classification problem whereby each comment can belong to one or more class at the same time.



## File Descriptions

- train.csv – Contains the training data with the comments and their binary labels
- test.csv – Contains data for which comment toxicity probabilities need to be predicted
- sample_submission.csv - a sample submission file in the correct format
