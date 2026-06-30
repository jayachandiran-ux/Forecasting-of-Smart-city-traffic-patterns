# 🚦 Forecasting of Smart City Traffic Patterns

## 📌 Overview

Traffic congestion is one of the biggest challenges in modern smart cities. Accurate traffic forecasting helps governments optimize traffic signals, reduce congestion, improve emergency response, and support infrastructure planning.

This project develops a Machine Learning model to predict future traffic volume at different city junctions using historical traffic data.

---

## 🎯 Problem Statement

Traffic volume varies based on several factors such as:

- Time of the day
- Day of the week
- Month
- Location (Junction)

Predicting future traffic enables better traffic management and supports smart city initiatives.

---

## 🎯 Objectives

- Analyze historical traffic data
- Perform data preprocessing and feature engineering
- Explore traffic patterns using visualizations
- Build a Machine Learning model for traffic prediction
- Evaluate model performance using regression metrics

---

## 📂 Dataset

The dataset contains traffic records collected from four different city junctions.

### Features

- **DateTime** – Date and time of traffic observation
- **Junction** – Junction ID
- **Vehicles** – Number of vehicles (Target Variable)
- **ID** – Unique record identifier

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Exploratory Data Analysis

The following visualizations were created during analysis:

- Traffic Volume Over Time
- Traffic by Hour
- Traffic by Day of Week
- Traffic by Junction
- Correlation Heatmap
- Actual vs Predicted Vehicles
- Feature Importance

---

## ⚙️ Feature Engineering

Time-based features were extracted from the DateTime column:

- Year
- Month
- Day
- Hour
- Day of Week

These features help the model learn temporal traffic patterns.

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Random Forest Regressor

### Model Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Train-Test Split
6. Model Training
7. Prediction
8. Model Evaluation

---

## 📈 Model Performance

| Metric | Score |
|----------|--------:|
| MAE | 2.40 |
| RMSE | 3.56 |
| R² Score | 0.969 |

The model achieved an **R² Score of approximately 96.9%**, indicating excellent prediction performance.

---

## 📁 Project Structure

```
Forecasting-of-Smart-city-traffic-patterns
│
├── images/
│   ├── traffic_over_time.png
│   ├── traffic_by_hour.png
│   ├── traffic_by_day.png
│   ├── traffic_by_junction.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── feature_importance.png
│
├── Forecasting_of_Smart_city_traffic_patterns.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/jayachandiran-ux/Forecasting-of-Smart-city-traffic-patterns.git
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```bash
Forecasting_of_Smart_city_traffic_patterns.ipynb
```

4. Run all cells sequentially.

---

## 📌 Future Improvements

- Use advanced time-series forecasting models such as LSTM or Prophet
- Deploy the model as a web application
- Integrate live traffic data using APIs
- Improve prediction accuracy with additional traffic features

---

## 📖 Key Learnings

- Traffic data preprocessing
- Feature engineering using DateTime
- Exploratory Data Analysis (EDA)
- Random Forest Regression
- Regression model evaluation
- Feature importance analysis
- Smart city traffic forecasting

---

## 🙌 Acknowledgements

This project was completed as part of the **UCT Machine Learning Internship** to explore real-world Smart City traffic forecasting using Machine Learning techniques.

---

## 👨‍💻 Author

**Jayachandiran**

AI & Data Science Student

GitHub: https://github.com/jayachandiran-ux
