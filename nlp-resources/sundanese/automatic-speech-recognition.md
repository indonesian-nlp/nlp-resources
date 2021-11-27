---
title: "Automatic Speech Recognition"
subtitle: "Sundanese Speech Recognition"
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
- Speech Recognition
categories:
# layout options: single or single-sidebar
layout: single-sidebar
---

## Models

| Name                          | Description                                                                                                                                                                 | Author        | Link                                                                      |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------------------------------------------------- |
| Wav2Vec2-Large-XLSR-Sundanese | Fine-tuned facebook/wav2vec2-large-xlsr-53 on the OpenSLR High quality TTS data for Sundanese. When using this model, make sure that your speech input is sampled at 16kHz. | Cahya Wirawan | [HuggingFace](https://huggingface.co/cahya/wav2vec2-large-xlsr-sundanese) |

## Datasets

| Name    | Description                                                                                                                                                                                                                          | Author                                                                                            | Link                                                   |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| OpenSLR | This data set contains transcribed audio data for Sundanese (~220K utterances). The data set consists of wave files, and a TSV file. The file utt_spk_text.tsv contains a FileID, UserID and the transcription of audio in the file. | Oddur Kjartansson and Supheakmungkol Sarin and Knot Pipatsrisawat and Martin Jansche and Linne Ha | [HuggingFace](https://huggingface.co/datasets/openslr) |
