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

## 📂 Project Structure
job-spam-ham-detection/
│
├── data/                  # Raw and preprocessed datasets
├── notebooks/             # Jupyter notebooks for EDA, training, and evaluation
├── models/                # Saved model weights and architecture
├── utils/                 # Custom preprocessing and evaluation scripts
├── requirements.txt       # Environment dependencies
└── README.md              # Project documentation

## 📌 Notes
- Designed for extensibility: swap in other classifiers or datasets with minimal changes
- Evaluation metrics are logged and visualized for interpretability

## 📧 Contact
Maintained by Nathanael Martinez 
📍 Pateros, Philippines
📫 [jp.martinez.nathanael123@gmail.com]