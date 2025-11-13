# 🩺 Breast Cancer Anomaly Detection

A lightweight **unsupervised anomaly detection** project using the Multivariate Gaussian Model to identify abnormal breast cancer cases. The model learns the normal data distribution and flags low-probability observations as potential anomalies.

---

## 🔍 Overview
- Applies **density estimation** to detect rare malignant patterns  
- Uses **multivariate Gaussian parameters** (mean + covariance)  
- Threshold (**ε**) selected by maximizing F1-score  
- Visualizes outliers that deviate from the main cluster

This approach demonstrates how simple unsupervised methods can reveal meaningful medical anomalies without relying on labels.

---

## 📊 Dataset
- **Wisconsin Breast Cancer Dataset (WBC)**  
- 569 samples, 30 standardized numeric features  
- Labels used only for evaluation (not for training)

---

## 🧠 Method Highlights
- Feature preprocessing & normalization  
- Gaussian probability density calculation  
- Automatic threshold tuning  
- Outlier detection & visualization  

---

## 🛠️ Technologies
**Python**, NumPy, Pandas, Matplotlib, Seaborn

