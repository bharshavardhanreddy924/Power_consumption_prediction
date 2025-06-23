# ⚡ Power Consumption Prediction using Machine Learning

This project aims to accurately predict power consumption using machine learning techniques. It leverages historical power usage data and weather metrics to forecast future electricity demand. The insights help stakeholders in **energy management**, **grid optimization**, and **cost forecasting**.

---

## 📌 Project Overview

With the growing concern for efficient energy usage and sustainability, forecasting electricity consumption has become critical. This project uses **supervised machine learning models** and **time-series data** to build an efficient power consumption prediction system.

The workflow includes:

- Data loading and preprocessing
- Time-series feature engineering
- Model training and evaluation
- Visualization of results
- Exporting trained models for future use
- Optional use of [**Orange**](https://orange.biolab.si/) for visual machine learning and comparative model analysis

---

## ✨ Key Features

- ✅ Cleaned and preprocessed time-series dataset
- 📊 Exploratory Data Analysis (EDA) with visualizations
- 🧱 Feature engineering based on date-time decomposition
- 🤖 Multiple regression models for performance comparison
- 🔁 Reusability via model export (`joblib`)
- 🧩 Orange integration for no-code ML pipeline visualization

---

## 🧠 Algorithms Used

Implemented and compared:

- 📈 Linear Regression
- 🌳 Decision Tree Regressor
- 🌲 Random Forest Regressor
- 🚀 Gradient Boosting Regressor

---

## 🟠 Orange Tool Integration

We also explored the use of **Orange**, a visual programming tool for machine learning, to:

- Load the same dataset
- Perform EDA and model training without writing code
- Compare models like Random Forest, SVR, and Ridge using test scores and ROC curves

This approach enables **non-programmers** to replicate or extend the work easily.

---

## 📁 Project Structure

Power_consumption_prediction/
│
├── dataset/ # CSV file with historical power consumption data
│ └── power_consumption.csv
│
├── notebooks/ # Jupyter notebooks for analysis & modeling
│ ├── eda.ipynb # Exploratory Data Analysis and visualization
│ └── model_training.ipynb # Model training, tuning and evaluation
│
├── saved_models/ # Exported trained models
│ └── model.pkl
│
├── utils.py # Utility functions (e.g., metrics, time-series features)
├── main.py # Main script to load model and make predictions
├── requirements.txt # Python library dependencies
└── README.md # Project documentation (this file)

yaml


## 🧪 How to Run

### 🔧 1. Clone the Repository

git clone https://github.com/bharshavardhanreddy924/Power_consumption_prediction.git
cd Power_consumption_prediction
📦 2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
📚 Optional: Open Jupyter Notebooks
