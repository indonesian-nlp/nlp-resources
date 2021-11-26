---
title: "Javanese Language Model"
subtitle: "Javanese Language Models and its Dataset"
excerpt: "Language Model is a model that computes probability of a sentence (sequence of words) or the probability of a next word in a sequence."
date: 2021-06-01
author: "Wilson Wongso, Steven Limcorn and AI-Research.id team"
draft: false
layout: list-sidebar
images:
- /blog/assets/css-grid-thumbnail.png
series:
- huggingface jax flax event
tags:
- gpt-2
- language model
categories:
# layout options: single or single-sidebar
layout: single-sidebar
---

## Masked Language Models

| Name                           | Description                                                                                                                                                        | Author        | Link                                                                       |
|--------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------------------------------------------------------------------------|
| Javanese BERT Small            | Javanese BERT Small is a masked language model based on the BERT model. It was trained on the latest (late December 2020) Javanese Wikipedia articles.             | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-bert-small)            |
| Javanese DistilBERT Small      | Javanese DistilBERT Small is a masked language model based on the DistilBERT model. It was trained on the latest (late December 2020) Javanese Wikipedia articles. | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-distilbert-small)      |
| Javanese RoBERTa Small         | Javanese RoBERTa Small is a masked language model based on the RoBERTa model. It was trained on the latest (late December 2020) Javanese Wikipedia articles.       | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-roberta-small)         |
| Javanese BERT Small IMDB       | Javanese BERT Small IMDB is a masked language model based on the BERT model. It was trained on Javanese IMDB movie reviews.                                        | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-bert-small-imdb)       |
| Javanese DistilBERT Small IMDB | Javanese DistilBERT Small IMDB is a masked language model based on the DistilBERT model. It was trained on Javanese IMDB movie reviews.                            | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-distilbert-small-imdb) |
| Javanese RoBERTa Small IMDB    | Javanese RoBERTa Small IMDB is a masked language model based on the RoBERTa model. It was trained on Javanese IMDB movie reviews.                                  | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-roberta-small-imdb)    |

## Causal/Generative Language Models

| Name                      | Description                                                                                                                                       | Author        | Link                                                                 |
|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------------------------------------------------------------------|
| Javanese GPT-2 Small      | Javanese GPT-2 Small is a language model based on the GPT-2 model. It was trained on the latest (late December 2020) Javanese Wikipedia articles. | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-gpt2-small)      |
| Javanese GPT-2 Small IMDB | Javanese GPT-2 Small IMDB is a causal language model based on the GPT-2 model. It was trained on Javanese IMDB movie reviews.                     | Wilson Wongso | [HuggingFace](https://huggingface.co/w11wo/javanese-gpt2-small-imdb) |

## Datasets
| Name         | Description                                                                                                                                                                                                                                                                                                                                                         | Author                                                                                                                                                            | Link                                                                       |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| mC4-sampling | This dataset builds upon the AllenAI version of the original mC4 and adds sampling methods to perform perplexity-based filtering on the fly. Please, refer to BERTIN Project.                                                                                                                                                                                       | BERTIN Project & Colin Raffel and Noam Shazeer and Adam Roberts and Katherine Lee and Sharan Narang and Michael Matena and Yanqi Zhou and Wei Li and Peter J. Liu | [HuggingFace](https://huggingface.co/datasets/bertin-project/mc4-sampling) |
| mC4          | A multilingual colossal, cleaned version of Common Crawl's web crawl corpus. Based on Common Crawl dataset: "[https://commoncrawl.org](https://commoncrawl.org)".                                                                                                                                                                                                   | Colin Raffel and Noam Shazeer and Adam Roberts and Katherine Lee and Sharan Narang and Michael Matena and Yanqi Zhou and Wei Li and Peter J. Liu                  | [HuggingFace](https://huggingface.co/datasets/mc4)                         |
| OSCAR        | OSCAR or Open Super-large Crawled ALMAnaCH coRpus is a huge multilingual corpus obtained by language classification and filtering of the Common Crawl corpus using the goclassy architecture. Data is distributed by language in both original and deduplicated form.                                                                                               | Ortiz Suárez, Pedro Javier and Romary, Laurent and Sagot, Benoit                                                                                                  | [HuggingFace](https://huggingface.co/datasets/oscar)                       |
| CC100        | This corpus is an attempt to recreate the dataset used for training XLM-R. This corpus comprises of monolingual data for 100+ languages and also includes data for romanized languages (indicated by *_rom). This was constructed using the urls and paragraph indices provided by the CC-Net repository by processing January-December 2018 Commoncrawl snapshots. | Wenzek, Guillaume and Lachaux, Marie-Anne and Conneau, Alexis and Chaudhary, Vishrav and Guzmán, Francisco and Joulin, Armand and Grave, Edouard                  | [HuggingFace](https://huggingface.co/datasets/cc100)                       |
| Wikipedia    | Wikipedia dataset containing cleaned articles of all languages. The datasets are built from the Wikipedia dump ([https://dumps.wikimedia.org/](https://dumps.wikimedia.org/)) with one split per language. Each example contains the content of one full Wikipedia article with cleaning to strip markdown and unwanted sections (references, etc.).                | Wikimedia Foundation                                                                                                                                              | [HuggingFace](https://huggingface.co/datasets/wikipedia)                   |
