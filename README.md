# Fake News Detector using BERT + LSTM

This project uses BERT embeddings with an LSTM classifier to detect fake news.

## Dataset
- `Fake.csv` and `True.csv` from Kaggle
- 45k total news articles

## Model Architecture
- `bert-base-uncased` embeddings
- LSTM (hidden_dim=128) + Fully Connected layer
- Trained with PyTorch

## Results
precision    recall  f1-score   support

        Fake       0.98      0.93      0.96      4710
        Real       0.93      0.98      0.96      4270

    accuracy                           0.96      8980
   macro avg       0.96      0.96      0.96      8980
weighted avg       0.96      0.96      0.96      8980
