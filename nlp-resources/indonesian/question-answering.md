---
title: "Indonesian Question Answering"
subtitle: "Indonesian Question Answering and its Datasets"
excerpt: "Building Systems that automatically answer questions posed by humans in a natural language"
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

# 

## Models
| Name                                                            | Description                                                                                             | Author | Link                                                                        |
|-----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|--------|-----------------------------------------------------------------------------|
| IndoBERT-Lite base fine-tuned on Translated SQuAD v2            | IndoBERT-Lite trained by Indo Benchmark and fine-tuned on Translated SQuAD 2.0 for Q&A downstream task. | Akmal  | [HuggingFace](https://huggingface.co/Wikidepia/indobert-lite-squad)         |
| IndoBERT-Lite-SQuAD base fine-tuned on Full Translated SQuAD v2 | IndoBERT-Lite trained by Indo Benchmark and fine-tuned on Translated SQuAD 2.0 for Q&A downstream task. | Akmal  | [HuggingFace](https://huggingface.co/Wikidepia/indobert-lite-squadx)        |
| SQuAD Bahasa Albert Model                                       | Finetuned Albert base language model with translated SQuAD. Based on huseinzol05's Albert Bahasa.       | Akmal  | [HuggingFace](https://huggingface.co/Wikidepia/albert-bahasa-cased-squad)   |
| SQuAD IndoBERT-Lite Base Model                                  | Fine-tuned IndoBERT-Lite from IndoBenchmark using Translated SQuAD datasets.                            | Akmal  | [HuggingFace](https://huggingface.co/Wikidepia/albert-bahasa-uncased-squad) |
| IndoBERT Base-Uncased fine-tuned on Translated Squad v2.0       | IndoBERT trained by IndoLEM and fine-tuned on Translated SQuAD 2.0 for Q&A downstream task.             | Rifky  | [HuggingFace](https://huggingface.co/Rifky/Indobert-QA)                     |

## Datasets
| Name    | Description                                                                                                                                                                                                                                                                                                                                                                         | Author                                                                                                                                 | Link                                                   |
|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| FacQA   | The goal of the FacQA dataset is to find the answer to a question from a provided short passage from a news article. Each row in the FacQA dataset consists of a question, a short passage, and a label phrase, which can be found inside the corresponding short passage. There are six categories of questions: date, location, name, organization, person, and quantitative.     | Ayu Purwarianti, Masatoshi Tsuchiya, and Seiichi Nakagawa                                                                              | [HuggingFace](https://huggingface.co/datasets/indonlu) |
| TyDi QA | TyDi QA is a question answering dataset covering 11 typologically diverse languages with 204K question-answer pairs. The languages of TyDi QA are diverse with regard to their typology -- the set of linguistic features that each language expresses -- such that we expect models performing well on this set to generalize across a large number of the languages in the world. | Jonathan H. Clark and Eunsol Choi and Michael Collins and Dan Garrette and Tom Kwiatkowski and Vitaly Nikolaev and Jennimaria Palomaki | [HuggingFace](https://huggingface.co/datasets/tydiqa)  |
| mLAMA   | This dataset provides the data for mLAMA, a multilingual version of LAMA. Regarding LAMA see [https://github.com/facebookresearch/LAMA](https://github.com/facebookresearch/LAMA). For mLAMA the TREx and GoogleRE part of LAMA was considered and machine translated using Google Translate, and the Wikidata and Google Knowledge Graph API.                                      | Nora Kassner and Philipp Dufter and Hinrich Schütze                                                                                    | [HuggingFace](https://huggingface.co/datasets/m_lama)  |
