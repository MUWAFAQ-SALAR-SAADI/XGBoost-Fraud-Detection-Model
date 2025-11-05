# XGBoost-Fraud-Detection-Model
Fraud Detection Bootcamp Project: A Python project detecting fraudulent transactions using a Kaggle dataset. Users upload their Kaggle API key to download data. It uses XGBoost, handles imbalanced classes, evaluates with ROC-AUC &amp; classification metrics, and includes a Gradio interface for interactive prediction.
# Fraud Detection Bootcamp Project

## Overview
This project is a Python-based fraud detection system using a synthetic transactions dataset from Kaggle.  
It uses **XGBoost** for classification and **Gradio** for a simple interactive web interface.

## Dataset
The dataset is hosted on Kaggle and is not included in the notebook.  
To access it, you must provide your **Kaggle API key**.

### Steps to set up the dataset:
1. Go to [Kaggle Account](https://www.kaggle.com/) → **Account** → **API** → **Create New API Token**.  
   This will download a file named `kaggle.json`.  
2. In the notebook, run the first cell to **upload your `kaggle.json` file**.  
3. The notebook will automatically download and unzip the dataset.

**Kaggle Dataset link:** [Fraud Detection Transactions Dataset](https://www.kaggle.com/datasets/samayashar/fraud-detection-transactions-dataset)

---

## Notebook Instructions
1. Open `fraud_detection.ipynb` in Google Colab.  
2. Upload your `kaggle.json` API key when prompted.  
3. Run all cells sequentially:
   - Data loading and preprocessing
   - Model training
   - Evaluation
   - Interactive Gradio interface

---

## Requirements
```bash
pip install pandas scikit-learn xgboost gradio matplotlib kaggle
