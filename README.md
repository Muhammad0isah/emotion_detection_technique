# Emotion Classification Technique in Restaurant Review Sentence

Multi-class sentiment analysis problem to classify texts into three emotion categories: joy, anger, and surprise. A project to go through different text classification techniques. This includes, LSTM neural networks and transfer learning using BERT (tensorflow keras).

# Datasets
*SemEval 2014 Restaurant dataset

### Neural Networks
* Data preprocessing: noise and punctuation removal, tokenization
* Word Embeddings: pretrained 300 dimensional word2vec ([link](https://fasttext.cc/docs/en/english-vectors.html))
* Deep Network: LSTM, biLSTM, CNN 

| Approach            | Accuracy | F1-Score |
| :------------------ |:--------:|:--------:|
| LSTM + w2v_wiki     |    ?     |    ?     |
| biLSTM + w2v_wiki   |    ?     |    ?     |
| CNN + w2v_wiki      |    ?     |    ?     |

### Transfer learning with BERT
Finetuning BERT for text classification

| Approach            | Accuracy | F1-Score |
| :------------------ |:--------:|:--------:|
| finetuned BERT      |    ?     |    ?     |