# Lab 07 - Sentiment Analysis with BoW and BERT

## Team Members
- **Soham Gaonkar** (23110314)
- **Chaitanya Sharma** (23110072)

## Repository
[GitHub Repository](https://github.com/Soham-Gaonkar/CS203_Lab_07)

## Overview
This repository contains the implementation of sentiment analysis models using:
- **Bag of Words (BoW)**
- **BERT Embeddings**

The models are trained and fine-tuned on two datasets and their performances are compared.

## Files in the Repository
- `data_prep.ipynb` - Data preprocessing, including batch-wise implementation.
- `main.ipynb` - Main training script for BoW and BERT models.
- `tb.ipynb` - TensorBoard visualization for tracking training metrics.
- `.gitignore` - Ignored files and folders.
- `Lab_07_Assignment_150325.pdf` - Report detailing the experiments and results.

## Model Training and Tuning
### Dataset 1
- **BoW Model** achieved an accuracy of **80.12%**.
- **BERT Model** achieved an accuracy of **86.55%**.

### Dataset 2 (Fine-tuned models)
- **Fine-tuned BoW Model** achieved **88.26%**.
- **Fine-tuned BERT Model** achieved **88.9%**.

## Key Observations
- Fine-tuning significantly improves performance on Dataset 2.
- BoW models rely on word frequency and lack context understanding.
- BERT embeddings capture deeper semantic meanings, leading to better performance.
- There is a trade-off between generalization and dataset specialization.

## TensorBoard Integration
TensorBoard is used for monitoring:
- Validation accuracy curves
- Validation loss curves
- Confusion matrices

## Conclusion
- **BERT outperforms BoW** due to its contextual embeddings.
- **Fine-tuning** is crucial for improving performance on a target dataset.
- **BoW is computationally efficient** but lacks deep language understanding.

For more details, refer to the **Lab_07_Assignment_150325.pdf**.

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/Soham-Gaonkar/CS203_Lab_07.git
   cd CS203_Lab_07
