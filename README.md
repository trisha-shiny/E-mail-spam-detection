# E-mail-spam-detection
A Machine Learning project to classify emails/SMS as **Spam** or **Ham (Not Spam)** using **Naive Bayes** and **TF-IDF Vectorization**.

---

## 🚀 Problem Statement
Spam emails affect productivity and security. This project builds a classifier to automatically detect spam emails.

---

## 🎯 Objective
- Preprocess email text (stopword removal, tokenization, TF-IDF vectorization).  
- Train a classifier using **Naive Bayes** or **SVM**.  
- Evaluate using accuracy, precision, and recall.  
- Achieve 90%+ accuracy for real-world deployment.  

---

## 📂 Dataset
**SMS Spam Collection dataset**:  
📥 [Download Dataset (Kaggle)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

Dataset columns:
- `label` → spam / ham  
- `message` → email/sms text  

---

## ⚙️ Requirements
Install dependencies:
```bash
pip install pandas scikit-learn matplotlib
