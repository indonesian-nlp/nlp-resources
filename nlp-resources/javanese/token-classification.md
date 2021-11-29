---
title: "Javanese Token Classification"
subtitle: "Models and its Dataset for Javanese Token Classification"
excerpt: "The Token classification Task is similar to text classification, except each token within the text receives a prediction. A common use of this task is Named Entity Recognition (NER)."
date: 2021-06-01
author: "Wilson Wongso, Steven Limcorn and AI-Research.id team"
draft: false
layout: list-sidebar
images:
- /blog/assets/css-grid-thumbnail.png
series:
- huggingface jax flax event
tags:
- BERT
- RoBERTa
- Language Model
categories:
# layout options: single or single-sidebar
layout: single-sidebar
---

## Datasets

| Name    | Description                                                                                                                                                                                                       | Author                                                                                                                                            | Link                                                   |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| WikiANN | WikiANN (sometimes called PAN-X) is a multilingual named entity recognition dataset consisting of Wikipedia articles annotated with LOC (location), PER (person), and ORG (organisation) tags in the IOB2 format. | Pan, Xiaoman and Zhang, Boliang and May, Jonathan and Nothman, Joel and Knight, Kevin and Ji, Heng & Rahimi, Afshin and Li, Yuan and Cohn, Trevor | [HuggingFace](https://huggingface.co/datasets/wikiann) |
