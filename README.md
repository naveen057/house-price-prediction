# 🏠 House Price Prediction

A machine learning application that predicts house prices based on property features. The project includes data analysis, model training, model persistence, and an interactive Streamlit application for making predictions.

## 📌 Project Overview

House prices depend on several property characteristics such as area, number of bedrooms, bathrooms, and other relevant features.

This project uses historical housing data to train a machine learning regression model and provide price predictions for new property inputs.

## 🎯 Objectives

* Analyze historical house-price data
* Perform data preprocessing and exploratory analysis
* Train a machine learning regression model
* Evaluate model performance
* Save the trained model for reuse
* Build an interactive prediction application using Streamlit

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Jupyter Notebook**
* **Streamlit**
* **Joblib**
* **Matplotlib / Seaborn**

## 🔄 Project Workflow

```text
Housing Dataset
      ↓
Data Exploration
      ↓
Data Preprocessing
      ↓
Feature Selection
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Save Trained Model
      ↓
Streamlit Application
      ↓
House Price Prediction
```

## 📂 Project Structure

```text
house-price-prediction/
│
├── Training.ipynb
├── app.py
├── kc_house_data.csv
├── save_model.joblib
├── requirements.txt
├── README.md
└── .gitignore
```

## 🤖 Machine Learning Model

The project uses a supervised machine learning regression approach to learn the relationship between property features and house prices.

The trained model is saved using **Joblib** and loaded by the Streamlit application to generate predictions.

> Update this section with the exact model name used in `Training.ipynb` (for example, Linear Regression, Random Forest Regressor, XGBoost, etc.).

## 📊 Model Evaluation

Add the actual evaluation results from your notebook here.

| Metric   |          Result |
| -------- | --------------: |
| R² Score | **0.7690 (76.90%)** |


> Use the actual values from your notebook. Do not add estimated results.

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/naveen057/house-price-prediction.git
```

### 2. Navigate to the project

```bash
cd house-price-prediction
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your browser.

## 🔮 Future Improvements

* Compare multiple regression algorithms
* Perform hyperparameter tuning
* Improve feature engineering
* Add model performance visualizations
* Add prediction history
* Deploy the application online
* Add batch prediction functionality

## 👨‍💻 Author

**Naveen**

GitHub: https://github.com/naveen057
