# 💳 Fraud Detection in Online Transactions      using Machine Learning

> A final year dissertation project submitted in April 2024 by Ansh Dankhara, Kenil Dhola, and Fenil Kakadiya as part of the IMSc(IT) program at GLS University.

---

## 📊 Project Overview

This project explores the application of machine learning algorithms to detect fraudulent credit card transactions in real-time. The rapid shift to digital payments has made fraud prevention a high-priority challenge. Our model aims to increase detection accuracy while minimizing false positives.

We used real-world data from Kaggle and evaluated three supervised learning algorithms:

* Support Vector Machine (SVM)
* Random Forest
* Logistic Regression

**Best achieved accuracy: 98.99% (Logistic Regression)**

---

## 🔹 Objectives

* Detect fraudulent transactions effectively.
* Handle highly imbalanced datasets.
* Compare algorithm performance.
* Maintain user data privacy and ethical standards.

---

## 📊 Dataset

* **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* **Size**: 284,807 transactions
* **Fraud Cases**: 492 (0.172%)
* **Features**: PCA-transformed variables + Time & Amount
* **Target**: `Class` (1 = Fraud, 0 = Non-Fraud)

---

## 📈 Algorithms Used

### ✅ Logistic Regression

* Simple and interpretable
* Best performance with 98.99% accuracy

### ✅ Random Forest

* Ensemble method of decision trees
* 97.98% accuracy, great for handling imbalance

### ✅ Support Vector Machine (SVM)

* Suitable for binary classification
* Also achieved 97.98% accuracy

---

## 🔢 Methodology

1. **Data Collection**
2. **Preprocessing** (handling nulls, normalization, feature engineering)
3. **Exploratory Data Analysis (EDA)**
4. **Model Training & Testing**
5. **Evaluation** using:

   * Precision, Recall, F1-Score
   * ROC-AUC Curve
6. **Cross-Validation & Tuning**

---

## 🔝 Key Results

| Algorithm           | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 98.99%   |
| Random Forest       | 97.98%   |
| SVM                 | 97.98%   |

---

## 🤝 Ethical Considerations

* Data privacy was respected throughout the project.
* Compliance with best practices for handling sensitive financial data.

---

## 🌍 Future Scope

* Integrating deep learning (CNNs/RNNs)
* Real-time fraud detection APIs
* Federated learning for privacy
* Cross-industry fraud pattern sharing

---

## 📑 Authors

* **Ansh Dankhara**  (202101619010014)
* **Kenil Dhola**    (202101619010017)
* **Fenil Kakadiya** (202101619010025)

---

## 🔗 Resources

* [Final Report (PDF)](./DOCUMENTATION.pdf)
* [Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

> "By combining machine learning with ethical practices, we move closer to a safer digital economy."

