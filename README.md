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



## 📌 Abstract

This project explores the design and optimization of speech recognition models tailored for keyword spotting tasks. By comparing multiple deep learning architectures and evaluating the impact of preprocessing and augmentation techniques, this work aims to identify efficient and accurate solutions for real-time speech classification.


## 🧪 Experimental Setup

- **Dataset:** Google Speech Commands v0.01 (30 classes, ~65K samples)
- **Feature Extraction:** MFCC with 13 coefficients, noise injection, time shifting
- **Train/Validation/Test Split:** 80/10/10
- **Frameworks Used:** TensorFlow, Keras, Librosa
- **Hardware:** Trained on NVIDIA GPU (if applicable, else say CPU)


## 📈 Results Summary

| Model                    | Accuracy | F1 Score | Notes |
|-------------------------|----------|----------|-------|
| CNN                     | 89.12%   | 0.88     | Strong baseline |
| LSTM                    | 87.45%   | 0.86     | Slower, less efficient |
| GRU                     | 88.02%   | 0.87     | Similar to LSTM, faster training |
| CNN-BiLSTM-Attention    | 92.11%   | 0.91     | Best balance of accuracy and robustness |
| CNN-Transformer         | 91.78%   | 0.90     | Performs well under noise |


## 📌 Citation

If you use this repository or any part of this work in your research, projects, or publications, please consider citing it as follows:

