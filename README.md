# 🎓 Student Performance & Risk Prediction (OULAD)

An end-to-end Machine Learning project utilizing the Open University Learning Analytics Dataset (OULAD) to predict student academic outcomes and identify at-risk students early in the semester.

## 🚀 Key Features
* **Machine Learning Pipeline:** Built and optimized robust predictive models (XGBoost and LightGBM) using Optuna for hyperparameter tuning.
* **Explainable AI (XAI):** Integrated SHAP (SHapley Additive exPlanations) values to provide transparent, interpretable explanations for model decisions at both global and local levels.
* **Interactive Dashboard:** Developed a comprehensive web application using Streamlit for Exploratory Data Analysis (EDA), model performance tracking, and real-time student risk prediction.

## 📁 How to Run Locally

Due to GitHub's file size restrictions, the raw dataset files (`.csv`, `.zip`) and heavy model history files are not included in this repository.

To set up and run the project on your local machine, please follow these steps:

1. **Download the Data:** Get the OULAD dataset from [Kaggle](https://www.kaggle.com/datasets/anulnd/open-university-learning-analytics-dataset).
2. **Extract Files:** Unzip the downloaded file and place all the `.csv` files directly into the root directory of this project.
3. **Install Dependencies:** Open your terminal and install the required Python packages by running:
   ```bash
   pip install -r requirements.txt
