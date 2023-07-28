# Information Retrieval Project

## Overview
This project is made through the course of Modern Information Retrieval of Dr. Mahdieh Soleymani Baghshah. 
This repository contains the implementation of an Information Retrieval project completed in three phases. The project focuses on various techniques for document classification, search and retrieval, clustering, and other advanced retrieval methods. Each phase is described below along with the implemented techniques and evaluation metrics.

## Phase 1 & 2: Document Classification and Retrieval

### Classification using Naive Bayes

In this phase, we implemented the Naive Bayes classification algorithm to classify documents into different categories. The model leverages the probabilistic approach of Naive Bayes to make accurate category predictions.

### Classification using Neural Network (FastText Embeddings)

We explored the use of neural networks, specifically FastText, to create document embeddings. These embeddings were used to classify documents into different categories with improved accuracy.

### Classification using Language Model (BERT)

In this phase, we employed BERT (Bidirectional Encoder Representations from Transformers), a powerful language model, to perform document classification. BERT's contextual embeddings enhanced the accuracy of the classification process significantly.

### Search and Retrieve Documents

We implemented three search methods to retrieve documents from the dataset based on user queries:

1. **Okapi BM25:** A classic ranking function for information retrieval based on term frequency and inverse document frequency.

2. **LTC-LNC:** An advanced retrieval method that leverages term frequency and document length normalization.

3. **LTN-LNN:** Another retrieval method that incorporates term frequency and the cosine similarity measure.

### Clustering

We explored two clustering methods to group similar documents together:

1. **K-means Clustering:** A popular unsupervised clustering algorithm that partitions the documents into K clusters.

2. **Hierarchical Clustering:** A method that builds a tree-like structure to group documents based on their similarity.

## Phase 3: Advanced Retrieval and Ranking

### Implement Crawler

In this phase, we developed a web crawler to collect data from online source (semanticscholar.org) to expand the dataset for further analysis.

### Personalized PageRank

We implemented the Personalized PageRank algorithm to improve the ranking of documents based on personalized user preferences.

### Personalized Search

Building upon the Personalized PageRank, we created a personalized search functionality that provides more relevant results based on individual user preferences.

### Authors Ranking

We introduced an authors ranking system to identify influential authors within the dataset based on their contributions and citations.

### Recommender System

We developed two types of recommender systems:

1. **Content-Based Recommender:** This system suggests documents to users based on the similarity of their content to the user's preferences.

2. **Collaborative Filtering Recommender:** This system suggests documents to users based on the preferences of similar users.

## Evaluation Metrics

Throughout each phase, we used the following evaluation metrics to assess the performance of the implemented algorithms:

- Accuracy
- Precision
- Recall
- F1-score
- Mean Average Precision (MAP)
- Normalized Discounted Cumulative Gain (NDCG)
