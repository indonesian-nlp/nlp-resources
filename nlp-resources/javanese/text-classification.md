---
title: "Text Classification"
subtitle: "Models and its Dataset for Javanese Text Classification"
excerpt: "Text Classification is the processing of labeling or organizing text data into groups. It forms a fundamental part of Natural Language Processing."
date: 2021-06-01
author: "Wilson Wongso, Steven Limcorn and AI-Research.id team"
draft: false
layout: list-sidebar
images:
- /blog/assets/css-grid-thumbnail.png
series:
- huggingface jax flax event
tags:
- GPT-2
- BERT
- RoBERTa
- Language Model
categories:
# layout options: single or single-sidebar
layout: single-sidebar
---

## Models

| Name                                      | Description                                                                                                                                             | Author        | Link                                                                                  |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------------------------------------------------------------- |
| Javanese BERT Small IMDB Classifier       | Javanese BERT Small IMDB Classifier is a movie-classification model based on the BERT model. It was trained on Javanese IMDB movie reviews.             | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-bert-small-imdb-classifier)       |
| Javanese DistilBERT Small IMDB Classifier | Javanese DistilBERT Small IMDB Classifier is a movie-classification model based on the DistilBERT model. It was trained on Javanese IMDB movie reviews. | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-distilbert-small-imdb-classifier) |
| Javanese GPT-2 Small IMDB Classifier      | Javanese GPT-2 Small IMDB Classifier is a movie-classification model based on the GPT-2 model. It was trained on Javanese IMDB movie reviews.           | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-gpt2-small-imdb-classifier)       |
| Javanese RoBERTa Small IMDB Classifier    | Javanese RoBERTa Small IMDB Classifier is a movie-classification model based on the RoBERTa model. It was trained on Javanese IMDB movie reviews.       | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-roberta-small-imdb-classifier)    |

## Datasets

| Name          | Description                                                                                                                                                                                                                                                               | Author                                                                                                                          | Link                                                               |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| IMDb Javanese | Large Movie Review Dataset translated to Javanese. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. | Wilson Wongso & Maas, Andrew L. and Daly, Raymond E. and Pham, Peter T. and Huang, Dan and Ng, Andrew Y. and Potts, Christopher | [HuggingFace](https://huggingface.co/datasets/w11wo/imdb-javanese) |
| WiLI-2018     | WiLI-2018, the Wikipedia language identification benchmark dataset, contains 235000 paragraphs of 235 languages. The dataset is balanced and a train-test split is provided.                                                                                              | Thoma, Martin                                                                                                                   | [HuggingFace](https://huggingface.co/datasets/wili_2018)           |
