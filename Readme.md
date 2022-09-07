# Research Article Recommender

Zimu Su

## Abstract

A recommendation system is built for providing potential interesting research articles to the users of academic citation software. The system can facilitate academic article searching and attract more users to utilize the software. Topic modeling is firstly conducted based on total datasets of articles abstracts using Non-Negative Matrix Factorization (NMF) method. The recommendation system is then built based on cosine similarity of topic scores. The system is preliminarily validated according to selected articles of different topics.

## Design

The observation in the dataset stands for the research article abstract. Preprossing is done by word tokenization and selecting noun as part of speech. Term Frequency-Inverse Document Frequency (TF-IDF) is used for words account.

## Data

The dataset is originally collected from [Kaggle]([https://www.kaggle.com/datasets/abisheksudarshan/topic-modeling-for-research-articles?select=Test.csv]). Each row stands for a research article, as well as its abstract and subject tags.

## Algorithms

* Word tokenization and noun selection.
* Count word using TF-IDF.
* Use NMF for topic modeling.
* Compute the highest scores of cosine similarity for a selected article and shows the provided articles.

## Tools

Python Pandas, Scikit learn, NLTK, Numpy

## Communication

The project is under supervision of Julia Lintern and delivered on 9/7/2022
