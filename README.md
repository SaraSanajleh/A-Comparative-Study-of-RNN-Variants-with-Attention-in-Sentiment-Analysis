# A-Comparative-Study-of-RNN-Variants-with-Attention-in-Sentiment-Analysis
📌 Project Overview

This project investigates binary sentiment classification using deep learning models.
We implemented and compared multiple RNN-based architectures in PyTorch, leveraging pre-trained GloVe embeddings.

The models explored include:

LSTM

BiLSTM

BiRNN

BiLSTM + Attention

⚙️ Implementation

Preprocessing with GloVe word embeddings.

PyTorch implementations of RNN variants.

Hyperparameter tuning and evaluation using accuracy, precision, recall, and F1-score.

Comparative analysis of training complexity vs. performance.

📊 Results (Test Set)

LSTM → Accuracy: ~76.5%

BiRNN → Accuracy: ~70.7%

BiLSTM → Accuracy: ~78.0%

BiLSTM + Attention → Accuracy: ~79.9% (Best)

➡️ Conclusion:

BiLSTM significantly outperforms LSTM and BiRNN.

Adding Attention further boosts performance and interpretability.

Trade-off: Higher accuracy comes with increased training time and parameters.

👥
