# Project Results and Visualisations

This folder contains the results obtained from the comparative evaluation of four deep learning architectures for multi-class news topic classification using the AG News dataset.

## Models Evaluated

The following models were implemented and evaluated:

1. Multi-Layer Perceptron (MLP)
2. One-Dimensional Convolutional Neural Network (1D-CNN)
3. Long Short-Term Memory (LSTM)
4. Transformer Encoder

## Contents

This folder contains the graphical representations and evaluation results generated during the experiments.

The visualisations include:

- **Test Accuracy Comparison:** Compares the test accuracy achieved by all four models.
- **Macro F1-Score Comparison:** Shows the macro F1-score of each architecture.
- **Validation Accuracy Comparison:** Compares the best validation accuracy recorded during training.
- **Training Time Comparison:** Shows the recorded training duration for each model.
- **Inference Time Comparison:** Compares the recorded inference time across the four architectures.
- **Confusion Matrices:** Class-wise classification performance and misclassification patterns, where included.

## Key Experimental Results

| Model | Test Accuracy |
|---|---:|
| MLP | 91.49% |
| 1D-CNN | 91.29% |
| LSTM | 91.03% |
| Transformer Encoder | 91.24% |

The MLP achieved the highest test accuracy of 91.49%, closely followed by the 1D-CNN and Transformer Encoder.

## Purpose

These results provide a visual and quantitative comparison of the four architectures and support the analysis presented in the final project report.

**Note:** All results are based on the saved experimental outputs from the project notebook. Training and inference times should be interpreted with the timing limitations discussed in the final report.
