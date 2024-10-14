
# Bangla Sentiment Analysis using LSTM

This repository contains the implementation of a sentiment analysis model for Bangla text. The model classifies text into different sentiment categories, such as positive and negative using LSTMs.


## Dataset

The dataset used here was used in the paper [Sentiment Classification in Bangla Textual Content: A Comparative Study](https://arxiv.org/abs/2011.10106). It was collected from [here](https://github.com/banglanlp/bangla-sentiment-classification/tree/main)

## Methodology

The model was trained using the following steps:

    1. Train-test split
    2. Data preprocessing (Split tokenization, building vocab, padding)
    3. Model architecture design (LSTM layers)
    4. Training the LSTM model on the training set
    5. Evaluating the model's performance

## Results
The model achieved an accuracy of 0.74. We used a larger training set, dropouts, simpler architecture and early stopping to reduce overfitting as much as possible. However, we can see from our loss curves that the model still largely overfits. Better results can be obtained if we used pretrained models (eg. BERT) and word embeddings (eg. GloVe, Word2Vec).





