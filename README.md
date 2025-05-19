# 🍷 Wine Quality Prediction

A machine learning project that predicts the quality of wine using various classification algorithms such as Random Forest and Support Vector Machine (SVM). The goal is to accurately classify wines as good or bad based on physicochemical properties.

---

## 📌 Project Highlights

- Built using **Random Forest**, **SVM**, and other classification models
- Performed **feature selection** and **hyperparameter tuning** to improve model accuracy
- Used **EDA (Exploratory Data Analysis)** to understand data trends and correlations
- Evaluated model using **confusion matrix**, **precision**, **recall**, and **ROC AUC**
- Demonstrated the **full ML pipeline**: data cleaning → training → evaluation → deployment

---

## 🔧 Tools & Technologies

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn (for EDA)
- Scikit-learn (ML algorithms & metrics)
- Jupyter Notebook / Google Colab

---

## 📊 Dataset

- [Wine Quality Data Set - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- Contains physicochemical tests and quality ratings (0–10)

---

## 📁 Project Structure

```bash
wine-quality-prediction/
│
├── wine_quality.ipynb          # Jupyter Notebook with full code
├── README.md                   # Project documentation
├── winequality-red.csv         # Dataset (can also be downloaded during runtime)
├── requirements.txt            # (Optional) Package dependencies
└── models/                     # (Optional) Saved ML models
