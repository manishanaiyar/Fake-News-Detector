# Fake News Detector using BERT + LSTM

This project uses BERT embeddings with an LSTM classifier to detect fake news.

## Dataset
- `Fake.csv` and `True.csv` from Kaggle
- 45k total news articles

## Model Architecture
- `bert-base-uncased` embeddings
- LSTM (hidden_dim=128) + Fully Connected layer
- Trained with PyTorch

## Model Performance
The Fake News Detector using BERT + LSTM achieved high performance on the test set:

Metric	Fake Class	Real Class
Precision	0.98	0.93
Recall	0.93	0.98
F1-Score	0.96	0.96
Support	4710	4270

Overall Accuracy: 96%
Macro Average:

Precision: 0.96

Recall: 0.96

F1-Score: 0.96

Weighted Average:

Precision: 0.96

Recall: 0.96

F1-Score: 0.96
