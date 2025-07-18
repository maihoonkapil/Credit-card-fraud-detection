# Credit Card Fraud Detection 🕵️‍♂️💳

This project builds machine learning models to detect fraudulent credit card transactions using an imbalanced dataset. It uses oversampling techniques like **SMOTE**, and models like **Logistic Regression** and **Random Forest**, with **SHAP** for explainability.

---

## 📊 Problem Statement

Credit card fraud is a growing concern. This project aims to accurately classify transactions as fraudulent or legitimate, even with highly imbalanced data.

---

## 🔍 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Records: 284,807 transactions
- Fraudulent: 492 (~0.17%)

---

## 🧠 Models Used

- Logistic Regression
- Random Forest Classifier
- SMOTE for balancing
- Evaluation with Precision, Recall, ROC-AUC

---

## 📈 Performance

- **Precision:** 96%
- **ROC-AUC:** 0.94
- Feature impact visualized using **SHAP values**

---

## 🛠️ Tech Stack

- Python
- Pandas, Scikit-learn, Imbalanced-learn
- Matplotlib, Seaborn
- SHAP (for interpretability)

---

## 💡 Project Highlights

- Tackled extreme class imbalance using SMOTE
- Built interpretable models
- Applied SHAP to visualize model decision logic
- Scalable pipeline for training & evaluation

---

## 🚀 Run It Yourself

```bash
# Clone the repo
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Credit_Card_Fraud_Detection.ipynb
