# Semantic Search Engine

This repository contains the code and resources for a Semantic Search Engine implemented with Elasticsearch. The search engine is designed to index and search vectors representing various documents, such as those related to retail, finance, and healthcare. It utilizes Elasticsearch for efficient indexing and retrieval of data.

## Overview

- **Jupyter Notebooks:** This project includes two Jupyter notebooks:
  1. `json_format.ipynb`: In this notebook, we preprocess raw JSON data. We remove stopwords, perform lemmatization, vectorize the text, and normalize the vectors. After preprocessing, the vectors are combined with the original JSON data.
  2. `Elasticsearch.ipynb`: This notebook focuses on mapping and indexing the preprocessed vectors into Elasticsearch. It also demonstrates how to perform semantic searches within the indexed data.

- **JSON Files:** The project includes six JSON files:
  - `Retail_DP_Sample.json`
  - `Finance_DP_Sample.json`
  - `Health_DP_Sample.json`
  - `combined_retail.json`
  - `combined_finance.json`
  - `combined_health.json`
  These files contain data related to the respective domains and are used for indexing and searching.

- **Elasticsearch Setup:** To set up Elasticsearch locally, you can use the provided `docker-compose.yml` file.

## Usage

Follow these steps to use the Semantic Search Engine:

1. Preprocess your raw JSON data using `json_format.ipynb`.
2. Use the output data with Elasticsearch for indexing and mapping the vectors using `Elasticsearch.ipynb`.
3. Perform semantic searches within the indexed data.

## Requirements

List any dependencies, libraries, or software that users need to have installed to run your project successfully. For example:

- Python 3.7 or higher
- Jupyter Notebook
- Elasticsearch
- json
- numpy
- sklearn
- nltk
- sentence_transformers

