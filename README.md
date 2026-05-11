
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,50:1E3A8A,100:06B6D4&height=220&section=header&text=UNI-AI&fontSize=68&fontColor=F8FAFC&animation=fadeIn&fontAlignY=38&desc=AI-Powered%20Student%20Risk%20Prediction%20Platform&descAlignY=58&descColor=93C5FD&descSize=22" />

<br/>

![Python](https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=FFD43B)
![Streamlit](https://img.shields.io/badge/Streamlit-0F172A?style=for-the-badge&logo=streamlit&logoColor=38BDF8)
![XGBoost](https://img.shields.io/badge/XGBoost-1E3A8A?style=for-the-badge&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-06B6D4?style=for-the-badge&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-2563EB?style=for-the-badge)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter%20Tuning-0EA5E9?style=for-the-badge)

<br/>

> **Predict • Explain • Intervene**
> AI platform for early student dropout detection and academic risk analysis.

<br/>

![Best Model](https://img.shields.io/badge/Best%20Model-XGBoost%20Tuned-2563EB?style=flat-square)
![ROC-AUC](https://img.shields.io/badge/ROC--AUC-97.92%25-06B6D4?style=flat-square)
![F1 Score](https://img.shields.io/badge/F1%20Score-92.01%25-1D4ED8?style=flat-square)
![Students](https://img.shields.io/badge/Students-32K+-0F172A?style=flat-square)
![Models](https://img.shields.io/badge/Models-9%20Classifiers-0284C7?style=flat-square)

</div>

---

# UNI-AI

UNI-AI is an end-to-end machine learning platform built on the **OULAD dataset** to predict student academic risk and dropout probability using explainable AI.

The system compares **9 ML models**, applies **Optuna hyperparameter tuning**, builds an **ensemble model**, and explains predictions using **SHAP** through an interactive Streamlit dashboard.

---

## Dataset

### OULAD — Open University Learning Analytics Dataset

- 32,593 students
- 28 engineered features
- 7 relational tables
- Student demographics, assessments, VLE engagement, and registration data

Dataset Download:

https://analyse.kmi.open.ac.uk/open-dataset

---

## Run Locally

```bash
git clone https://github.com/mohesham100/UNI-AI.git
cd UNI-AI

pip install -r requirements.txt

streamlit run appp.py
```

Place all OULAD CSV files inside the project root directory before running the app.

---

# Platform Features

## Dashboard

Comprehensive analytics dashboard with:
- Pass & withdrawal rates
- Risk distribution
- Engagement analysis
- Model leaderboard
- AI-generated insights

![Dashboard](dashboard.png)

---

## Student Risk Prediction

Predict student dropout probability using:
- Demographics
- Assessment performance
- VLE engagement
- Registration timing

Includes:
- SHAP explainability
- Personalized intervention recommendations

![Prediction](prediction.png)

---

## Model Performance

Comparison between:
- XGBoost
- LightGBM
- Random Forest
- Gradient Boosting
- SVM
- KNN
- Logistic Regression
- MLP Neural Network
- Decision Tree
- Ensemble models

Visualizations include:
- ROC curves
- Bar charts
- Radar plots

![Model Performance](model_perf.png)

---

## EDA & Insights

Exploratory analysis across all OULAD tables:
- Result distribution
- Education level impact
- IMD analysis
- Gender breakdown
- Engagement patterns
- Feature importance

![EDA](eda.png)

---

## SHAP Explainability

Explain model decisions using:
- SHAP beeswarm plots
- Waterfall charts
- Dependence plots

![SHAP](shap.png)

---

# Model Results

| Model | Accuracy | ROC-AUC |
|------|----------|---------|
| XGBoost (Tuned) | **92.01%** | **97.92%** |
| LightGBM (Tuned) | 91.61% | 97.87% |
| Gradient Boosting | 91.41% | 97.78% |
| Random Forest | 91.00% | 97.53% |
| SVM | 90.98% | 96.84% |
| Logistic Regression | 89.78% | 95.89% |

> Hyperparameter tuning performed using Optuna TPE optimization.

---

# Tech Stack

| Category | Technologies |
|---|---|
| Data Processing | Pandas, NumPy |
| Machine Learning | XGBoost, LightGBM, Random Forest, SVM, KNN |
| Tuning | Optuna |
| Explainability | SHAP |
| Frontend | Streamlit |
| Visualization | Plotly, Matplotlib, Seaborn |

---

# Project Structure

```bash
UNI-AI/
│
├── app.py
├── project.ipynb
│
└── pages_code/
    ├── dashboard.py
    ├── predict.py
    ├── model_perf.py
    ├── eda.py
    ├── shap_page.py
    └── utils.py
```

---

# Author

## Mo Hesham

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammad-hesham-550792345)

[![GitHub](https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohesham100)

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohammadhisham091@gmail.com)
