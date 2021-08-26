# Automatic Speech Recognition

## Models

| Name                         | Description                                                                                                                                                                | Author        | Link                                                                     |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------------------------------------------------ |
| Wav2Vec2-Large-XLSR-Javanese | Fine-tuned facebook/wav2vec2-large-xlsr-53 on the OpenSLR High quality TTS data for Javanese. When using this model, make sure that your speech input is sampled at 16kHz. | Cahya Wirawan | [HuggingFace](https://huggingface.co/cahya/wav2vec2-large-xlsr-javanese) |

## Datasets

| Name    | Description                                                                                                                                                                                                                         | Author                                                                                            | Link                                                   |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| OpenSLR | This data set contains transcribed audio data for Javanese (~185K utterances). The data set consists of wave files, and a TSV file. The file utt_spk_text.tsv contains a FileID, UserID and the transcription of audio in the file. | Oddur Kjartansson and Supheakmungkol Sarin and Knot Pipatsrisawat and Martin Jansche and Linne Ha | [HuggingFace](https://huggingface.co/datasets/openslr) |
