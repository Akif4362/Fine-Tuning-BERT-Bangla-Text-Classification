
# Fine-Tuning BERT for Bangla Text Classification
This repository contains the implementation of a sentiment analysis model for Bangla text. The model classifies text into different sentiment categories, such as positive and negative. We use PyTorch and Huggingface transformers library for this purpose


## Dataset

The dataset was collected from [here](https://github.com/banglanlp/bangla-sentiment-classification/tree/main/data/multichannel_bsentiment)

## Methodology

The model was trained using the following steps:

    1. installing and importing libraries
    2. fetching data and EDA
    3. pre-processing data (tokenization)
    4. creating model and training (using HuggingFace transformers)
    5. evaluating the model's performance (accuracy, f1 score, confusion matrix)

## Results
We trained our model for 3 epochs. The model achieved an accuracy of 0.76. The BERT model was not pretrained on Bangla language. To get better results we can fine tune the model on a larger dataset or use a model pretrained on multi languages. 
 Epoch | Training Loss | Test Loss | Accuracy | F1 Score 
 ---   | ---           | ---       | ---      | ---
1      | 0.5934        | 0.5897    | 0.7248   | 0.7208
2      | 0.5333        | 0.5208    | 0.7569   | 0.7482
3      | 0.4478        | 0.5062    | 0.7656   | 0.7642
