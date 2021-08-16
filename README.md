# Machine Translation (English sentence to Hindi sentence)
This project was made as a part of my individual projects.

#### -- Project Timeline: [July 2021]
#### -- Project Status: [Completed]


## Problem Statement
Machine translation refers to the automatic translation of a sequence from one language to another. There are many architectures through which the task of translating a sequence can be achieved, ex. Recurrent Neural Networks (RNN), Long Short Term Memory (LSTM), Sequence to Sequence models, Transformers. Here, in this project, I have mainly used the Sequence to Sequence model with attention.
The project aims to translate the source language into the target language. In this project, the source language is taken as English text, and the target language is taken as Hindi text. 

## Project Objective
The project objective is to understand and implement the sequence to sequence model with attention, a state-of-the-art deep learning architecture.

## Tech Stack
- Python 3.7.10 or above
- Numpy, Pandas
- [Pytorch](https://pytorch.org/) 1.9.0 or above
- CUDA 10.2 for faster training
- Google Colab
- Seq2Seq with Attention

## Dataset
The dataset can be found in the data directory of this repository. Dataset contains

- `Hindi_English_Truncated_Corpus.csv.zip` zip file. 

### Dataset Description
The csv file contains two columns:
1. English text
2. Hindi text

There are total of `39881` rows in the datset. `80%` of the dataset was used for training and the remaining dataset was used for testing purpose.

## Results </br>
![Result](https://user-images.githubusercontent.com/26361028/129594680-df020ff7-6179-4856-b1b4-b8047fd488b9.png)

## Testing the accuracy of the model via Bleu Score

### Interpretation of Bleu Score
![Interpretation](https://user-images.githubusercontent.com/26361028/129594993-b513190a-9d5d-4ff8-b3c6-5fac4a21cbe9.png)

### Obtained Bleu Score on test dataset: 42.7

## Conclusion: 
The model was able to achieve high quality translation.

## Authors
- Palash Mahendra Kamble - [palash04](https://github.com/palash04/)
