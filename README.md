This repository contains the implementation of two novel methods for Speech Emotion Recognition (SER) using the Wav2vec2.0 model, as discussed in our paper. The methods include Classifier Combination and Attention-Based Feature Fusion, which have been evaluated using the EMODB dataset.

## Description

The code is divided into two Jupyter notebooks:
1. **Classifier Combination.ipynb**: Implements the Classifier Combination method where outputs from multiple Dimension Reduction Modules (DRMs) are combined to make the final prediction.
2. **Feature Fusion.ipynb**: Implements the Attention-Based Feature Fusion method, where features from different DRMs are concatenated and processed with an attention mechanism for classification.

Both notebooks require a Weights & Biases (Wandb) account for experiment tracking and use the EMODB dataset for training and evaluation.
