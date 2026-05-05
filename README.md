# 🧬 Cancer Prediction using XGBoost

## 📌 Project Overview

Early detection of cancer is critical for effective treatment.
This project builds a machine learning model to classify tumors as **malignant or benign** using clinical features.

The model leverages **XGBoost**, a high-performance gradient boosting algorithm widely used in real-world ML applications.

---

## 🎯 Objective

* Develop a reliable classification model for cancer prediction
* Minimize false negatives (critical in medical diagnosis)
* Analyze feature importance to understand key predictors

---

## 📊 Dataset

* Breast Cancer Dataset (from Scikit-learn)
* Total samples: **569**
* Features: 30 numerical attributes describing tumor characteristics

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* Matplotlib

---

## 🚀 Model Workflow

1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Train-test split
4. Model training using XGBoost
5. Model evaluation
6. Feature importance analysis

---

## 📈 Results

* **Accuracy:** 89.47%
* **ROC-AUC Score:** 0.90

### 📊 Confusion Matrix

```text
[[39  3]
 [ 9 63]]
```

### 🔍 Key Insight

The model achieves **high recall for malignant cases**, which is crucial in healthcare applications to reduce the risk of missed diagnoses.

---

## 📊 Feature Importance

![Feature Importance](feature_importance.png)

The model identifies key features such as tumor radius, perimeter, and area as strong predictors of cancer diagnosis.

---

## 📁 Project Structure

```text
cancer-prediction-xgboost/
│
├── notebooks/
│   └── XGBoost_Cancer_project.ipynb
│
├── feature_importance.png
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

```bash
git clone https://github.com/kalpanaMu/cancer-prediction-xgboost.git
cd cancer-prediction-xgboost
pip install -r requirements.txt
jupyter notebook
```

---

## 💡 Why XGBoost?

XGBoost is chosen for:

* High accuracy on structured data
* Built-in regularization
* Ability to handle feature interactions effectively

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Cross-validation
* Model deployment using Streamlit
* Adding more medical datasets

---

## 👤 Author

**Kalpana Mu**

---

## ⭐ If you found this useful

Give this repo a ⭐ and feel free to connect!
