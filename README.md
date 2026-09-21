# 🚗 Car Price Prediction

A machine learning regression project that predicts the price of a car based on its characteristics and specifications. The project demonstrates an end-to-end machine learning workflow, from data preparation and exploratory analysis to model training and evaluation.

## 📌 Project Overview

Car prices depend on several factors, including the vehicle's make, model, year, engine specifications, transmission type, and other characteristics.

The goal of this project is to build a regression model capable of predicting a vehicle's price from these features.

This project was developed as part of the **Machine Learning Zoomcamp 2026**.

## 🎯 Problem Statement

Given information about a vehicle, predict its price using machine learning regression techniques.

**Target variable:** `price`

**Problem type:** Supervised Learning — Regression

## 📊 Dataset

The dataset contains information about different vehicles and their characteristics.

Some of the features include:

- Make
- Model
- Year
- Engine HP
- Engine Cylinders
- Transmission Type
- Vehicle Style
- Market Category
- Number of Doors
- Driven Wheels
- Fuel Type
- Vehicle Size
- Vehicle Width
- Vehicle Height
- Highway MPG
- City MPG

The dataset was cleaned and prepared before being used for model training.

## 🔎 Exploratory Data Analysis

The dataset was explored to understand:

- Distribution of car prices
- Relationships between vehicle features and price
- Missing values
- Duplicate records
- Numerical and categorical features
- Outliers and unusual values
- Features that may have a strong relationship with the target variable

## 🛠️ Data Preparation

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected the dataset structure and data types.
3. Checked for missing values.
4. Checked for duplicate records.
5. Handled missing values appropriately.
6. Separated the target variable from the input features.
7. Prepared numerical and categorical features for machine learning.
8. Split the data into training and validation/test sets.

## 🤖 Machine Learning Model

This project uses **regression** because the target variable, car price, is a continuous numerical value.

The model was trained using the prepared vehicle features and evaluated on unseen data.

The project focuses on building a reproducible machine learning pipeline rather than simply fitting a model to the available data.

## 📏 Model Evaluation

The model was evaluated using regression metrics such as:

- **RMSE (Root Mean Squared Error)** — measures the typical magnitude of prediction errors.
- **MAE (Mean Absolute Error)** — measures the average absolute difference between predicted and actual prices.
- **R² Score** — measures how much of the variation in car prices is explained by the model.

The final evaluation results can be found in the project notebook.

## 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

## 📁 Project Structure

```text
Car-Price-Prediction/
│
├── data/
│   └── car_price_dataset.csv
│
├── notebooks/
│   └── car_price_prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

> The exact structure may vary depending on the files included in the repository.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/TUGUMEFAROUK/Car-Price-Prediction.git
```

Navigate into the project:

```bash
cd Car-Price-Prediction
```

Create and activate a virtual environment:

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially to reproduce the analysis and model training process.

## 📈 Results

The trained regression model was able to learn the relationship between vehicle characteristics and their corresponding prices.

The notebook contains the detailed experiments, preprocessing steps, model training process, and evaluation results.

## 🚀 Future Improvements

Possible improvements include:

- Hyperparameter tuning
- Testing additional regression algorithms
- Feature selection
- More advanced feature engineering
- Cross-validation
- Model deployment as a web API
- Building a user interface for real-time car price predictions

## 👨‍💻 Author

**Tugume Farouk**

Computer Science Student | Aspiring Machine Learning & AI Engineer

GitHub: [TUGUMEFAROUK](https://github.com/TUGUMEFAROUK)

## 📄 License

This project is intended for educational and learning purposes.
