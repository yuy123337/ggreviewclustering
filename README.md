
# Simiarity and Clustering
This repository contains code for analyzing restaurant reviews using TF-IDF, K-means clustering, and LDA topic modeling. This repository contains two Jupyter notebook with some repetitive contents due to several trials, one has appliced Latent Dirichlet Allocation (LDA) to topic modeling, extracting key themes from restaurant reviews for both Chinese and Japanese cuisines. The PDF file is also in this repository

This trails aims to analyze reviews of Chinese and Japanese restaurants on food-related themes.

Elbow method was used to determine the optimal number of clusters (k) for k-means. 

# Data
The review dataset contains customer reviews for Chinese and Japanese restaurants, including text data and metadata like review scores, cuisine type, and other relevant features. The dataset is large and includes millions of records.

Due to the large size of the data, it could not be uploaded directly to this repository. However, you can download the data from the source (or request access) and place it in the appropriate directory for processing. The dataset is expected to be stored in CSV or JSON format and should be pre-processed (e.g., cleaned, tokenized) before running the analysis.

# For tf-idf
TF-IDF seems to be a bit meaningless for my data as it 
The methodology presented by Gabriela Nathania H. et al. focuses on summarizing hotel reviews using two main approaches: extractive summarization based on TF-IDF scores and feature extraction through Adjective-Noun Pairing, which I could try but failed. 

The clustering approach could be used to group reviews into similar topics or sentiments. 

Future thoughts:
Adjective-Noun Pairing: Extracting adjectives and nouns can help identify the key features and their qualities that customers comment on. For example, pairing "delicious" with "ramen" or "slow" with "service" could help in understanding specific aspects of customer satisfaction or dissatisfaction?

