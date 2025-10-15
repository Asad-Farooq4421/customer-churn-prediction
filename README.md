# 🎯 Customer Churn Prediction

## 📊 Project Overview
An end-to-end machine learning project that predicts customer churn for a telecommunications company. This system analyzes customer data to identify at-risk customers and provides actionable insights through an interactive dashboard.

![Dashboard Screenshot](images/dashboard-screenshot.png)

## 🚀 Live Demo
[🔗 Try the Live Dashboard](https://your-username-customer-churn.streamlit.app/) *[Add your Streamlit Cloud URL after deployment]*

## 🎯 Business Impact
- **Reduce customer acquisition costs** by 15-20% through proactive retention
- **Identify at-risk customers** with 85%+ accuracy
- **Enable data-driven decisions** for customer retention strategies

## 📈 Model Performance
- **Accuracy**: 85.2%
- **Precision**: 0.83
- **Recall**: 0.79
- **F1-Score**: 0.81
- **AUC-ROC**: 0.88

## 🛠 Tech Stack
- **Programming**: Python 3.8+
- **Machine Learning**: Scikit-learn, Imbalanced-learn
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Dashboard**: Streamlit
- **Data Processing**: Pandas, NumPy

## 📁 Project Structure
customer-churn-prediction/
│
├── data/
│   ├── raw/
│   │   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   └── processed/
│       └── (cleaned data will be saved here)
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_model_evaluation.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── model_trainer.py
│   └── utils.py
│
├── app.py
├── requirements.txt
└── README.md

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Asad-Farooq4421/customer-churn-prediction.git
cd customer-churn-prediction

pip install -r requirements.txt

streamlit run app.py