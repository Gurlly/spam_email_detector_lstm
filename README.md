# 📬 Job Spam-Ham Detection

A machine learning pipeline for classifying job-related emails as **spam** or **ham (legitimate)** using curated datasets, balanced preprocessing, and interpretable evaluation metrics.

---

## 🚀 Project Overview

This project builds a robust spam detection model tailored for job-related email content. It includes:
- 📦 **Dataset curation**: Balanced spam/ham samples with domain-aware token filtering  
- 🧹 **Preprocessing pipeline**: Text normalization, tokenization, and vocabulary pruning  
- 🧠 **Modeling**: LSTM-based classifier with tuned hyperparameters  
- 📊 **Evaluation**: Precision, recall, F1-score, and confusion matrix on validation set  
- 📁 **Reproducibility**: Virtual environment and requirements tracking

---

## 🛠️ Setup Instructions
1. **Clone the repository** 
2. **Create and activate virtual environment**
    - `python -m venv venv`
    - `source venv/bin/activate`
3. **Install Dependencies**
    - `pip install -r requirements.txt`
4. **Run the notebook**
    - `JOB_SPAM_DETECTION.ipynb` for model creation and evaluation.
    - `Model_Test.ipynb` for real-world data testing purposes.

## 📌 Notes
- Designed for extensibility: swap in other classifiers or datasets with minimal changes
- Evaluation metrics are logged and visualized for interpretability
- If some packages were not installed successfully, try to install it manually.

## 📧 Contact
Maintained by Nathanael Martinez 
📍 Pateros, Philippines
📫 [jp.martinez.nathanael123@gmail.com]
