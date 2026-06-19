# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict house prices using Machine Learning techniques based on various property features such as area, number of bedrooms, bathrooms, stories, parking spaces, furnishing status, and other amenities.

The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization to identify the factors that significantly influence house prices.

---

## 🎯 Problem Statement

Real estate buyers and sellers often struggle to determine the fair value of a property. Estimating prices manually can be inaccurate and time-consuming.

The goal of this project is to build a regression model that can accurately predict house prices based on property characteristics and provide insights into the most important pricing factors.

---

## 📂 Dataset

The dataset contains information about residential properties, including:

* Area
* Number of Bedrooms
* Number of Bathrooms
* Stories
* Parking Spaces
* Main Road Access
* Guest Room Availability
* Basement Availability
* Hot Water Heating
* Air Conditioning
* Preferred Area
* Furnishing Status
* House Price (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## 📊 Project Workflow

### 1. Data Preprocessing

* Load dataset
* Check dataset dimensions
* Handle missing values
* Remove duplicate records
* Encode categorical variables using One-Hot Encoding

### 2. Exploratory Data Analysis (EDA)

* House price distribution
* Correlation analysis
* Price vs Area relationship
* Price vs Bedrooms analysis
* Feature importance investigation

### 3. Model Building

Two regression models were implemented:

#### Linear Regression

A statistical model that establishes a linear relationship between house features and price.

#### Random Forest Regressor

An ensemble learning method that combines multiple decision trees to improve prediction accuracy.

### 4. Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Visualizations

The project includes several visualizations:

* Distribution of House Prices
* Correlation Heatmap
* Price vs Area Scatter Plot
* Price vs Bedrooms Box Plot
* Actual vs Predicted Price Comparison

---

## 🔑 Key Insights

* Area is the strongest factor affecting house prices.
* Bathrooms and number of stories also have significant influence.
* Furnished properties generally command higher prices.
* Houses with similar bedroom counts can still have large price variations due to other property features.
* Random Forest captures complex relationships better than simple linear models.

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn missingno
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run `House_Price_Prediction.ipynb`

---

## 📁 Project Structure

```text
House_Price_Prediction/
│
├── House_Price_Prediction.ipynb
├── Housing.csv
├── price_distribution.png
├── correlation_heatmap.png
├── price_vs_area.png
├── price_by_bedrooms.png
├── actual_vs_predicted.png
└── README.md
```

---

## 📌 Future Improvements

* Hyperparameter tuning
* Feature selection techniques
* Cross-validation
* XGBoost and Gradient Boosting models
* Deployment using Flask/Streamlit
* Real-time house price prediction web application

---
