# Spam and Ham Email Detection Project

## Overview
This project focuses on developing an email classification system that distinguishes between spam and ham (non-spam) emails. The goal is to accurately identify and filter out spam while allowing legitimate emails to reach the inbox.

This repository contains code and resources for building a spam mail detection model using logistic regression. 

## Dataset

The dataset used for this analysis consists of a collection of emails labeled as spam or ham. Each email is represented as text data. The dataset is split into a training set and a test set for model training and evaluation.

## Requirements

To run the code and reproduce the analysis, the following dependencies are required:

-> Python 3

-> NumPy

-> Pandas

-> scikit-learn

![download (6)](https://github.com/suryaaaprakash/spam-mail-detection/assets/147717009/83c96613-a288-4106-8892-26427a71b706)


## Methodology

1. We used scikit-learn library, which provides a range of machine learning algorithms and tools for text classification tasks.

2. We took the dataset 'Mail_CSV' that contains two columns: 'Message' and 'Category', where 'Message' represents the text of each message, and 'Category' indicates whether it is SPAM or HAM.

3. We load the dataset using pandas and split it into features (X) and labels (Y).

4. The data is split into training and testing sets using train_test_split from scikit-learn

5. We convert the text messages into numerical features using TfidVectorizer from scikit-learn

6. We train the spam classifier model using the Logistic Regression algorithm, which is commonly used for text classification tasks.

7. At last we evaluate the model's performance by predicting labels for the testing set and comparing them to the actual labels.

8. We calculate the accuracy score and the confusion matrix to assess the model's performance.

## Result
