# 🛒 Demand Forecasting in Supply Chain Management

## 📌 Overview
Predicting weekly product demand using Walmart Sales data 
and Machine Learning techniques.

## 📊 Dataset
- Source: Walmart Sales Dataset (Kaggle)
- Records: 6435 rows
- Period: 2010–2012 (Weekly)

## 🤖 Models Used
- Random Forest → MAPE: 9.81%
- XGBoost → MAPE: 10.91%
- Prophet → MAPE: 4.18% 🏆

## 🏆 Best Model
Prophet with 4.18% MAPE (95.82% accuracy)

## 🛠️ Tech Stack
- Python 3.8+
- Pandas, NumPy, Scikit-learn
- XGBoost, Prophet
- Matplotlib, Seaborn
- Power BI (Dashboard)

## 📁 Project Structure
demand_forecasting/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── models/
└── outputs/

## ▶️ How to Run
1. Clone the repo
2. Install requirements: pip install -r requirements.txt
3. Open notebooks/01_main.ipynb
4. Run all cells
