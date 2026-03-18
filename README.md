# 🚨 Hybrid Financial Fraud Detection System

A machine learning and deep learning-based hybrid system designed to detect fraudulent financial transactions using both supervised and unsupervised learning techniques.

---

## 📌 Overview

Financial fraud is a growing challenge in digital transactions. This project presents a **hybrid fraud detection framework** that combines anomaly detection and classification models to improve detection accuracy and reduce false positives.

The system integrates:
- Supervised Learning → Detect known fraud patterns  
- Unsupervised Learning → Detect unknown/anomalous behavior  

---

## 🎯 Objectives

- Detect fraudulent transactions with high accuracy  
- Reduce false positives in fraud detection  
- Handle imbalanced financial datasets effectively  
- Build a scalable and adaptable fraud detection system  

---

## 🧠 Models Used

### 🔹 Supervised Learning
- Decision Tree Classifier  
- Random Forest Classifier  
- Logistic Regression  
- MLP Neural Network  

### 🔹 Unsupervised Learning
- Autoencoder (Deep Learning)  
- K-Means Clustering  
- Principal Component Analysis (PCA)  

---

## ⚙️ Hybrid Approach

The system follows a **two-stage hybrid architecture**:

1️⃣ **Anomaly Detection (Autoencoder)**  
- Learns normal transaction patterns  
- Flags anomalies using reconstruction error  

2️⃣ **Classification (Random Forest / MLP)**  
- Uses anomaly score + features  
- Classifies transactions as fraud or legitimate  

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | AUC-ROC |
|------|----------|----------|--------|----------|--------|
| MLP Neural Network | 99.83% | 0.811 | 0.720 | 0.763 | 0.9955 |
| Random Forest | 99.82% | 0.9349 | 0.5688 | 0.7072 | 0.9905 |
| Decision Tree | 99.74% | ~0.66 | ~0.66 | ~0.66 | 0.8292 |
| Logistic Regression | 99.59% | 0.333 | 0.0536 | 0.0924 | 0.9291 |

---

## 📂 Dataset

- Source: Kaggle Fraud Detection Dataset  
- Transactions from 2019–2020  
- Includes both legitimate and fraudulent transactions  

---

## 🔍 Key Insights

- Fraud detection is a highly **imbalanced classification problem**  
- Accuracy alone is not a reliable metric  
- **MLP Neural Network** achieved best overall performance  
- **Random Forest** achieved highest precision (low false positives)  
- Hybrid models improve detection of **unknown fraud patterns**

---

## 🛠️ Tech Stack

- Python  
- Scikit-learn  
- TensorFlow / Keras  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 📊 Workflow

1. Data Collection  
2. Data Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Training (ML + DL)  
6. Hybrid Model Integration  
7. Evaluation & Comparison  

---

## 🚀 Future Improvements

- Real-time fraud detection system using APIs  
- Deployment using Flask/Django  
- Integration with streaming systems (Kafka)  
- Explainable AI (SHAP/LIME)  

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit pull requests.

---

## 📬 Contact

If you found this project useful, feel free to connect with me on LinkedIn!

---

## ⭐ Acknowledgements

- Kaggle for dataset  
- Scikit-learn & TensorFlow communities  

---

## 📌 License

This project is for academic and research purposes.
