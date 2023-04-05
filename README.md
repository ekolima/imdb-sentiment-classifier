# IMBD Sentiment Analysis
This repository includes experiments for sentiment analysis, using the IMBD Dataset.

---
## Logistic regression
Developed a simple binary classifier using logistic regression, with scikit-Learn.


## Feed-Forward Neural Netword
Developed a Feed-Forward Neural Network with GloVe (300d) embeddings, using Pytorch.


## Bidirectional stacked RNN (LSTM/GRU cells)
Developed a Bidirectional stacked RNN with LSTM and GRU cells and GloVe (300d) embeddings, using Pytorch.


## BERT Finetuning
Fine tuned BERT to classify IMDB reviews, using Hugging Face Pytorch. On top of finetuning BERT for sentiment analysis, it has been also finetuned for a question answering task as it is described at [this paper](https://arxiv.org/pdf/2001.11985.pdf). Instead of Freebase data, the model was trained with Wikidata data.
