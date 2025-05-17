# DESIGNING-EFFICIENT-SPEECH-RECOGNITION-MODELS-EVALUATING-ARCHITECTURES-AND-OPTIMIZATION-STRATEGIES


This repository contains a comparative study of various deep learning models for speech command recognition. It includes exploratory data analysis (EDA), preprocessing using MFCCs, and training models like CNN, LSTM, GRU, CNN-BiLSTM-Attention, and CNN-Transformer hybrids.

## 📂 Repository Structure

| Notebook | Description |
|----------|-------------|
| `MFCC.ipynb` | Preprocessing pipeline using MFCC feature extraction with augmentation (noise injection, time shifting). |
| `LSTM_EDA.ipynb` | EDA and model training using Long Short-Term Memory (LSTM) networks. |
| `GRU_EDA.ipynb` | EDA and model training using Gated Recurrent Units (GRUs). |
| `CNN-BiLSTM-Attention.ipynb` | CNN frontend with BiLSTM and Attention layer for enhanced keyword spotting. |
| `CNN_Transformer_EDA.ipynb` | Hybrid CNN-Transformer model architecture and analysis. |

## 🧠 Objectives

- Extract MFCC features and augment the dataset.
- Evaluate and compare model performance on the Google Speech Commands dataset.
- Investigate trade-offs between accuracy, model complexity, and inference time.

## 📊 Models Compared

- CNN
- LSTM
- GRU
- CNN + BiLSTM + Attention
- CNN + Transformer

## 🧪 Key Metrics

- Accuracy
- F1 Score
- Per-class performance
- Robustness under noisy conditions

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
