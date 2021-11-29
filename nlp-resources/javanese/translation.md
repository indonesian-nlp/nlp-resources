---
title: "Javanese Machine Translation"
subtitle: "Models and its Dataset for Javanese Machine Translation"
excerpt: "Machine Translation is the task of automatically converting one natural language into another, preserving the meaning of the input text, and producing fluent text in the output language."
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
- Machine Translation
- Opus
- T5
- Language Model
categories:
# layout options: single or single-sidebar
layout: single-sidebar
---

## Models

| Name           | Description                                             | Author                                                           | Link                                                              |
| -------------- | ------------------------------------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------------- |
| OPUS-MT-MUL-EN | Machine translation from multiple languages to English. | Language Technology Research Group at the University of Helsinki | [HuggingFace](https://huggingface.co/Helsinki-NLP/opus-mt-mul-en) |
| OPUS-MT-EN-MUL | Machine translation from English to multiple languages. | Language Technology Research Group at the University of Helsinki | [HuggingFace](https://huggingface.co/Helsinki-NLP/opus-mt-en-mul) |

## Datasets

| Name                                             | Description                                                                                                                                                                                                                                                                                                                                                                                                                  | Author                                                                 | Link                                                       |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------- |
| Ubuntu                                           | A parallel corpus of Ubuntu localization files.                                                                                                                                                                                                                                                                                                                                                                              | J. Tiedemann                                                           | [HuggingFace](https://huggingface.co/datasets/opus_ubuntu) |
| Tatoeba                                          | This is a collection of translated sentences from [Tatoeba](https://tatoeba.org/en/).                                                                                                                                                                                                                                                                                                                                        | J. Tiedemann                                                           | [HuggingFace](https://huggingface.co/datasets/tatoeba)     |
| QED                                              | The QCRI Educational Domain Corpus (formerly QCRI AMARA Corpus) is an open multilingual collection of subtitles for educational videos and lectures collaboratively transcribed and translated over the AMARA web-based platform.                                                                                                                                                                                            | Qatar Computing Research Institute, Arabic Language Technologies Group | [HuggingFace](https://huggingface.co/datasets/qed_amara)   |
| The Universal Declaration of Human Rights (UDHR) | The Universal Declaration of Human Rights (UDHR) is a milestone document in the history of human rights. Drafted by representatives with different legal and cultural backgrounds from all regions of the world, it set out, for the first time, fundamental human rights to be universally protected. The Declaration was adopted by the UN General Assembly in Paris on 10 December 1948 during its 183rd plenary meeting. | UDHR & Joe Davison                                                     | [HuggingFace](https://huggingface.co/datasets/udhr)        |
