# SQuAD-SRC
This repository contains the dataset introduced in the paper [SQuAD-SRC: A Dataset for Multi-Accent Spoken Reading Comprehension](https://www.ijcai.org/proceedings/2023/0578.pdf)

SQuAD-SRC is an open-source, large-scale, naturally recorded, multi-accent spoken reading comprehension dataset. The objective is to predict the answer from the text-form context according to spoken queries. 

SQuAD-SRC is built upon [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/), an extractive MRC dataset on Wikipedia passages. We provide 98,169 spoken questions for the entire training and development set of SQuAD v1.1, allowing a direct performance comparison with existing MRC models.

To encourage accent diversity, the audio utterances in SQuAD-SRC are recorded by 24 qualified speakers from six different countries, including the US, UK, China, India, Japan, and Thailand. The audios are provided in raw waveform with a 16 kHz sampling rate and 16-bit encoding depth. The anonymous speaker id for each utterance (SPK001 to SPK024) is presented in the filename.

SQuAD-SRC poses new challenges for spoken reading comprehension, including addressing the semantic gap between two modalities, and the complexity and variations associated with complex human voices.

Please download the data [here](https://drive.google.com/drive/folders/1f95kfMInB1ohM33vGoHdlL_LRm6CFASz?usp=drive_link).
