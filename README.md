# DL-Arabic-Aspect-Sentiment-Polarity
This repository contains our Deep Learning course project re-implementing a published BERT-based model for **Arabic Aspect Sentiment Polarity Classification** (*Arabic aspect sentiment polarity classification using BERT*, 2022) on a different public Arabic ABSA dataset.

## Project Overview
- **Paper Re-implementation:** Rebuilds the published BERT-based aspect sentiment polarity classification architecture and training setup ([Arabic aspect sentiment polarity classification using BERT, 2022](https://link.springer.com/article/10.1186/s40537-022-00656-6)).
- **New Dataset Evaluation:** Applies the model to a separate public Arabic Aspect-Based Sentiment Analysis dataset ([IbrahimAljarrah/DataSet-Aspect-Based-Sentiment-Analysis](https://github.com/IbrahimAljarrah/DataSet-Aspect-Based-Sentiment-Analysis)).
- **Simpler Baseline:** Implements a lightweight TensorFlow/Keras LSTM baseline trained and evaluated on the exact same train/validation/test split to measure the performance gain of the Transformer architecture.
