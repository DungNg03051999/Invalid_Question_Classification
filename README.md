# Invalid_Question_Classification

## Project Overview:
An invalid question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is invalid:

Has a non-neutral tone.
Is disparaging or inflammatory.
Isn't grounded in reality.
Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers
The data includes the question that was asked, and whether it was identified as invalid (target = 1).

## Preprocessing data
The dataset is first divided into Train/Val/Test

Then tokenization process is taken in word-level

## Modelling
The model is built with GloVe Embedding layer, Bidirectional RNN with LSTM and GRU 
