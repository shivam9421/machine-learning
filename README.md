# 🤖 Machine Learning Projects

> Collection of ML projects | Python, Scikit-learn, Random Forest, Logistic Regression

## 📂 Projects

### 1. 📈 Stock Price Predictor
Predicts S&P 500 stock market movement using Random Forest Classifier.
- Fetched live data using `yfinance` library
- Built a backtesting system to evaluate model on historical data
- Feature engineering: rolling averages (2, 5, 60, 250, 1000 days) and trend features
- Used `predict_proba` with 60% confidence threshold
- **Precision: 53.96%** (baseline random = 50%)

**Tech:** Python, yfinance, Pandas, NumPy, Scikit-learn, Matplotlib

---

### 2. 🚢 Titanic Survival Prediction
Predicts whether a passenger survived the Titanic using Logistic Regression.
- Handled missing values (Age → mean, Embarked → mode, dropped Cabin)
- EDA with pie charts and bar graphs (gender-wise, class-wise survival analysis)
- Encoded categorical features (Sex, Embarked)
- **Accuracy: 81.61%** on test data

**Tech:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

### 3. 📚 Books Dataset — EDA
Exploratory data analysis on a books dataset.
- Cleaned missing values and duplicates
- Visualized genre distribution and publishing year trends
- Top 10 authors by average rating

**Tech:** Python, Pandas, Matplotlib

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)

---
⭐️ Star this repo if you find it helpful!
