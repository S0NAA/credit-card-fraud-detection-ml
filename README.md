# Credit Card Fraud Detection using Machine Learning

A machine learning project to detect fraudulent credit card transactions using imbalanced learning techniques. The project uses the Kaggle **Credit Card Fraud Detection** dataset and applies **SMOTE + Random Forest** to handle data imbalance and improve fraud classification.

---

## 📌 Project Overview
Credit card fraud is a major financial risk affecting millions of users worldwide.  
The goal of this project is to build a model that can accurately identify fraudulent transactions while minimizing false positives.

✔ Highly imbalanced dataset (<0.2% fraud)  
✔ Oversampling applied using **SMOTE**  
✔ Model trained using **Random Forest Classifier**  
✔ Performance evaluated using confusion matrix, classification report, and ROC-AUC

---

## 📂 Dataset
📌 Source: Kaggle — *Credit Card Fraud Detection*  
🔗 Download Link: https://www.kaggle.com/mlg-ulb/creditcardfraud

- Total rows: **284,807**
- Fraud cases: **492**
- Feature space: **PCA-transformed variables + Time + Amount**

> Note: Dataset is NOT uploaded to this repository due to GitHub file size limits.

---

## 🔧 Technologies Used
| Tool | Purpose |
|------|---------|
| Python | Data processing + modeling |
| Pandas, NumPy | Data preprocessing |
| Scikit-Learn | SMOTE, Random Forest, metrics |
| Matplotlib, Seaborn | Visualization |
| Jupyter Notebook | Experiment & evaluation |

---

## 🚀 Model Results
| Metric | Score |
|--------|------|
| Accuracy | ~99% |
| Recall (Fraud class) | ~83% |
| Precision (Fraud class) | ~90% |
| ROC-AUC Score | ~0.91 |

✅ High recall → More fraud is detected  
✅ Balanced with strong precision → Fewer false fraud alerts

---

## 📌 Confusion Matrix
[[56855    9]
[ 17       81]]

---

## ▶️ How to Run
```sh
git clone https://github.com/S0NAA/credit-card-fraud-detection-ml.git
cd credit-card-fraud-detection-ml
pip install -r requirements.txt
jupyter notebook
# Open fraud_detection.ipynb


(Add confusion matrix image here if available — upload to /images folder)

