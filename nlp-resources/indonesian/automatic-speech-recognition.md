---
title: "Automatic Speech Recognition"
subtitle: "Speech Recognition for Indonesian, Javanese and Sundanese."
excerpt: "Speech recognition is an interdisciplinary subfield of computer science and computational linguistics that develops methodologies and technologies that enable the recognition and translation of spoken language into text."
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

## Models
| Name                             | Description                                                                                                                                                                                                                                                                                         | Author                 | Link                                                                                         |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|----------------------------------------------------------------------------------------------|
| Wav2Vec2-Large-XLSR-Indonesian   | Fine-tuned facebook/wav2vec2-large-xlsr-53 on the Indonesian Artificial Common Voice dataset. When using this model, make sure that your speech input is sampled at 16kHz.                                                                                                                          | Cahya Wirawan          | [HuggingFace](https://huggingface.co/cahya/wav2vec2-large-xlsr-indonesian-artificial)        |
| Wav2Vec2-Large-XLSR-Indonesian   | Fine-tuned facebook/wav2vec2-large-xlsr-53 on the Indonesian Common Voice dataset and synthetic voices generated using Artificial Common Voicer, which again based on Google Text To Speech. When using this model, make sure that your speech input is sampled at 16kHz.                           | Cahya Wirawan          | [HuggingFace](https://huggingface.co/cahya/wav2vec2-large-xlsr-indonesian-mix)               |
| Wav2Vec2-Large-XLSR-Indonesian   | Fine-tuned facebook/wav2vec2-large-xlsr-53 on the Indonesian Common Voice dataset. When using this model, make sure that your speech input is sampled at 16kHz.                                                                                                                                     | Cahya Wirawan          | [HuggingFace](https://huggingface.co/cahya/wav2vec2-large-xlsr-indonesian)                   |
| Wav2Vec2-Large-XLSR-Indonesian   | This is the model for Wav2Vec2-Large-XLSR-Indonesian, a fine-tuned facebook/wav2vec2-large-xlsr-53 model on the Indonesian Common Voice dataset. When using this model, make sure that your speech input is sampled at 16kHz.                                                                       | Galuh                  | [HuggingFace](https://huggingface.co/Galuh/wav2vec2-large-xlsr-indonesian)                   |
| Wav2Vec2-Large-XLSR-Indonesian   | This is the model for Wav2Vec2-Large-XLSR-Indonesian, a fine-tuned facebook/wav2vec2-large-xlsr-53 model on the Indonesian Common Voice dataset. When using this model, make sure that your speech input is sampled at 16kHz.                                                                       | Indonesian NLP         | [HuggingFace](https://huggingface.co/indonesian-nlp/wav2vec2-large-xlsr-indonesian)          |
| Wav2Vec2-Large-XLSR-Indonesian   | This is the baseline for Wav2Vec2-Large-XLSR-Indonesian, a fine-tuned facebook/wav2vec2-large-xlsr-53 model on the Indonesian Common Voice dataset. It was trained using the default hyperparamer and for 2x30 epochs. When using this model, make sure that your speech input is sampled at 16kHz. | Indonesian NLP         | [HuggingFace](https://huggingface.co/indonesian-nlp/wav2vec2-large-xlsr-indonesian-baseline) |
| Wav2Vec2-Large-XLSR-53-Indonesia | Fine-tuned facebook/wav2vec2-large-xlsr-53 in Indonesia using the Common Voice When using this model, make sure that your speech input is sampled at 16kHz.                                                                                                                                         | Muhammad Agung Hambali | [HuggingFace](https://huggingface.co/ayameRushia/wav2vec2-large-xlsr-indonesia)              |
| Wav2Vec2-Large-XLSR-53-Indonesia | Fine-tuned facebook/wav2vec2-large-xlsr-53 in Indonesia using the Common Voice When using this model, make sure that your speech input is sampled at 16kHz.                                                                                                                                         | Muhammad Agung Hambali | [HuggingFace](https://huggingface.co/ayameRushia/wav2vec2-large-xlsr-indo)                   |
| XLSR-Indonesia                   | Wav2Vec2 fine-tuned on Common Voice ID Test.                                                                                                                                                                                                                                                        | Samsul Rahmadani       | [HuggingFace](https://huggingface.co/munggok/xlsr_indonesia)                                 |

## Datasets
| Name         | Description                                                                                                                                                                                                                                                | Author                                                                                                                                                | Link                                                        |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| Common Voice | The Common Voice dataset consists of a unique MP3 and corresponding text file. Many of the 9,283 recorded hours in the dataset also include demographic metadata like age, sex, and accent that can help train the accuracy of speech recognition engines. | Ardila, R. and Branson, M. and Davis, K. and Henretty, M. and Kohler, M. and Meyer, J. and Morais, R. and Saunders, L. and Tyers, F. M. and Weber, G. | [HuggingFace](https://huggingface.co/datasets/common_voice) |
