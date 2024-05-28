# Trending-Topics-in-Machine-Learning

## Overview
This project analyzes research paper titles to identify the most common words and underlying topics using Natural Language Processing (NLP) techniques. We use CountVectorizer for word frequency analysis and Latent Dirichlet Allocation (LDA) for topic modeling.

## Steps
### Data Preprocessing:
Load the research paper titles from a CSV file.
Remove punctuation and convert titles to lowercase.

### Word Frequency Analysis:
Use CountVectorizer to transform the processed titles into a document-term matrix.
Visualize the 10 most common words using a bar plot.

### Topic Modeling with LDA:
Fit an LDA model to the document-term matrix to identify topics.
Print the most important words for each topic.

The papers.csv Dataset can be found here: https://www.kaggle.com/datasets/benhamner/nips-papers 
