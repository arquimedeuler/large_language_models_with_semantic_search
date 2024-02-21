# Large Language Models with Semantic Search

This repository contains the notebooks from the course [Large Language Models with Semantic Search](https://learn.deeplearning.ai/large-language-models-semantic-search/) available on
[DeepLearning.AI](https://www.deeplearning.ai/). 

The structure of the course is as follows

## 1 Keyboard Search

A keyword search is performed using the Weaviate library to access the Wikipedia database. Some parameters such as the language, the number of results and the print format are modified.

## 2 Embeddings

We created embeddings for a list of words and for a series of questions and answers. Vector representation of embeddings for Wikipedia articles is presented.

**Note:** The files utils.py and wikipedia.pkl are required for compilation.

## 3 Dense Retrieval

A Vector Database for semantic Search for Dense Retrieval is implemented. A basic, a medium and a complicated query are presented.

**Note:** The files utils.py and test.ann are required for compilation.

## 4 ReRank

We improved keyword search and dense retrieval using ReRank. Each result shows the relevance_score.

**Note:** The file utils.py is required for compilation.

## 5 Generating Answers

We generated answers to specific questions based on an article by Andrew Ng on building a career in artificial intelligence, using embeddings and an efficient search index.

**Note:** The files utils.py and test.ann are required for compilation.

