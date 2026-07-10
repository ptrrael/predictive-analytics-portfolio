# 🚀 Predictive Analytics & Applied Data Science Portfolio

Welcome to my portfolio! I am **Elardian Putera Ramadhan (Putera)**, an undergraduate Statistics and Data Science student at IPB University. 

This repository is a curated collection of my end-to-end data science projects, bridging the gap between rigorous mathematical statistics and modern machine learning architectures. My focus lies in **Predictive Analytics, Optimization, and Deep Learning** to solve complex, real-world business and financial challenges.

---

## 🛠️ Tech Stack & Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1273CE?style=for-the-badge&logo=xgboost&logoColor=white)
![LSTM](https://img.shields.io/badge/LSTM-8A2BE2?style=for-the-badge&logo=keras&logoColor=white)
![Random Forest](https://img.shields.io/badge/Random_Forest-228B22?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

## 📁 Featured Projects

### 1. 🛡️ [Credit Card Fraud Detection using Random Forest](./credit-card-fraud)
A production-grade business analytics project focused on detecting fraudulent financial transactions in real-time.
* **Business Context:** Mitigating chargeback losses and operational risks in European credit card transactions while maintaining customer retention by minimizing False Positives.
* **Methodology:** Overcame an extreme class imbalance (only 0.17% fraud instances) by implementing a hybrid **SMOTE-Tomek Links** (0.8 ratio) resampling strategy. 
* **Modeling & Evaluation:** Trained a Random Forest classifier optimized via **Randomized Search** and **5-Fold Stratified Cross-Validation**. Evaluated strictly on minority-class-focused metrics (**AUPRC, ROC-AUC, F1-Score, MCC**).
* **Explainable AI (XAI):** Mapped feature importance and direction of impact using **SHAP values** to provide transparent, interpretable diagnostic signals for financial stakeholders.

### 2. 📈 [Quantitative Analysis & Stock Forecasting (Indonesian Big Four Banks)](./stock-forecasting)
An integration of financial econometrics and deep learning to model the trajectory of Indonesia's top banking assets (BBCA, BBRI, BMRI, BBNI).
* **Business Context:** Analyzing historical risk profiles via log return volatility, maximum drawdown (Value at Risk / VaR), and linear correlations to optimize algorithmic trading strategies and portfolio diversification.
* **Modeling:** Engineered a univariate **LSTM (Long Short-Term Memory)** neural network to project a 30-day price extrapolation.
* **Engineering Highlights:** Executed strict computational stability protocols by locking holistic random seeds and enabling deterministic operations in the TensorFlow environment, ensuring 100% model reproducibility.

### 3. ☎️ [Telecom Customer Churn Early Warning System](./customer-churn)
A comparative machine learning initiative aimed at identifying early customer attrition risks to optimize retention strategy costs (CRC vs. CAC).
* **Business Context:** Analyzed services, financial accounts, and demographic dimensions to uncover key retention drivers (e.g., the stickiness effect of "Partner" status).
* **Data Engineering:** Conducted a rigorous data audit, identifying a Missing at Random (MAR) phenomenon on billing attributes exclusively among early-tenure cohorts. Resolved this using distance-based **KNN Imputation**.
* **Modeling:** Benchmarked classical parametric algorithms (Logistic Regression) against advanced tree-based ensembles (**Random Forest & XGBoost**) to establish the most reliable decision boundary.

---

## 📂 Repository Structure
```text
📦 predictive-analytics-portfolio
 ┣ 📂 credit-card-fraud
 ┃ ┗ 📜 Deteksi Penipuan Kartu Kredit Menggunakan Random Forest.ipynb
 ┣ 📂 stock-forecasting
 ┃ ┗ 📜 Quantitative Analysis & Stock Price Forecasting of Indonesian Banking Sector.ipynb
 ┣ 📂 customer-churn
 ┃ ┗ 📜 Telecom Customer Churn Prediction.ipynb
 ┣ 📜 .gitignore
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

---

## ⚙️ How to Run

1. Clone this repository:
```bash
git clone [https://github.com/USERNAME/predictive-analytics-portfolio.git](https://github.com/USERNAME/predictive-analytics-portfolio.git)
```

2. Navigate to the project directory and install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook / JupyterLab to explore the `.ipynb` files.

---

## 📫 Let's Connect

I am always open to discussing data science, statistical optimization, and collaborative projects. Feel free to reach out!

* **LinkedIn:** [linkedin.com/in/puteraramadhan](https://linkedin.com/in/puteraramadhan)
* **Email:** [elardianputraramadhan02@gmail.com](https://mail.google.com/mail/?view=cm&fs=1&to=elardianputraramadhan02@gmail.com
)