# Network Intrusion Detection System

A machine learning based Network Intrusion Detection System built using the KDD Cup 1999 dataset to classify network traffic and identify different types of network attacks.

## Overview

This project applies data preprocessing, exploratory data analysis, feature engineering, machine learning, and deep learning techniques to network intrusion detection.

The workflow includes:

- Data preprocessing and cleaning
- Categorical feature encoding
- Feature scaling
- Exploratory data analysis
- Training and comparison of multiple ML models
- Hyperparameter tuning
- Model evaluation using classification metrics
- Deep learning experiments

## Dataset

The project uses the KDD Cup 1999 network intrusion detection dataset.

The dataset contains network connection records with features describing network traffic and attack types.

The `kddcup.txt` file contains the feature definitions used for processing the dataset.

## Machine Learning Models

The project compares multiple classification models, including:

- Random Forest
- Decision Tree
- AdaBoost
- Gradient Boosting
- HistGradientBoosting
- XGBoost

Additional deep learning experiments include:

- CNN
- GRU
- Autoencoder

## Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Results

Random Forest achieved approximately **99.76% accuracy**, while XGBoost achieved approximately **99.39% accuracy** in the evaluated experiments.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- TensorFlow
- Jupyter Notebook

## Project Structure

```text
Network-Intrusion-Detection-System/
│
├── NIDS.ipynb
├── kddcup.txt
├── requirements.txt
├── README.md
└── .gitignore

# How to Run
1. Clone the repository
git clone <repository-url>
cd Network-Intrusion-Detection-System

2. Create a virtual environment
python -m venv .venv

3. Activate the environment
Windows PowerShell:
.venv\Scripts\Activate.ps1

4. Install dependencies
pip install -r requirements.txt