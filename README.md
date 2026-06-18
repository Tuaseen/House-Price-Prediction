# 🏠 House Price Prediction using Machine Learning

## 📖 Overview

This project predicts house prices using Machine Learning regression algorithms. The model is trained on housing data and learns relationships between property features and their market prices.

The objective is to build an accurate and reliable house price prediction system that can assist buyers, sellers, and real-estate investors in making informed decisions.

---

## 🎯 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Multiple regression models
- Model evaluation and comparison
- House price prediction

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- CatBoost
- Jupyter Notebook

---

## 📊 Dataset

Dataset used:

**Kaggle House Prices - Advanced Regression Techniques**

The dataset contains various features such as:

- Lot Area
- House Quality
- Number of Rooms
- Garage Size
- Year Built
- Neighborhood
- Overall Condition

Target Variable:

- SalePrice

---

## 🤖 Machine Learning Models

The following models were explored:

- Linear Regression
- Random Forest Regressor
- CatBoost Regressor

---

## 📈 Evaluation Metrics

Models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── notebooks/
│   └── v2AILab.ipynb
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── outputs/
│   └── final_predictions.csv
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run `v2AILab.ipynb`

---

## 📋 Results

The trained model predicts house prices based on property characteristics and generates prediction outputs in:

```text
final_predictions.csv
```
