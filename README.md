# Kaggle Competition: Digit Recognizer

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-blue)](https://www.kaggle.com/code/hosanchau/cnn-dr)  
[![GitHub Code](https://img.shields.io/badge/Code-Repository-lightgrey)](https://github.com/Hugo0614/KaggleCompetition_DigitRecognizer)

## Overview
Participated in Kaggle's **Digit Recognizer** competition, aiming to classify handwritten digits (0-9) from 28x28 pixel images. Implemented a **PyTorch-based CNN** with advanced techniques including:

- **Data Augmentation**: Random rotations (±10°) and translations  
- **Anti-Overfitting**: Batch normalization, dropout layers, early stopping  
- **Optimization**: AdamW with adaptive learning rate scheduling  

## Results
- **Validation Accuracy**: 99.48%  
- **Kaggle Test Accuracy**: 99.2% (Top 8% on leaderboard)  
- **Training Efficiency**: Converged in 15 epochs with GPU acceleration  

## Key Features
- Stratified 80/20 train-validation split  
- Automated submission generation  
- Lightweight model for fast inference  

---

*Full implementation details available in the [Kaggle Notebook](https://www.kaggle.com/code/hosanchau/cnn-dr).*
