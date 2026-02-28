# 💎 Diamond Price Prediction – Advanced Case Study

## 📌 Project Overview

This project is an advanced end-to-end Machine Learning regression case study to predict the price of diamonds based on multiple features.

The objective is to analyze diamond characteristics and build a predictive model that estimates diamond prices accurately.

---

## 📊 Business Problem

Diamond pricing depends on various factors such as:

- Carat
- Cut
- Color
- Clarity
- Depth
- Table
- Dimensions (x, y, z)

Can we build a regression model to accurately predict diamond price?

This type of model can help:
- Jewelers
- E-commerce platforms
- Auction platforms
- Price estimation systems

---

## 📁 Dataset Information

The dataset contains:
- Carat (weight of diamond)
- Cut (quality)
- Color
- Clarity
- Depth
- Table
- Price (Target Variable)
- x, y, z dimensions

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
- Loaded CSV dataset
- Checked shape, info, summary statistics

### 2️⃣ Data Cleaning
- Checked missing values
- Handled zero values in dimensions
- Removed outliers

### 3️⃣ Exploratory Data Analysis (EDA)
- Carat vs Price analysis
- Correlation heatmap
- Distribution plots
- Category-wise comparison

### 4️⃣ Feature Engineering
- Label Encoding / One-Hot Encoding
- Feature scaling

### 5️⃣ Model Building
Applied regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 6️⃣ Model Evaluation
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## 📈 Results

Key Insights:

- Carat is the most important feature.
- Random Forest outperformed Linear Regression.
- Non-linear models capture pricing patterns better.

The model achieved strong R² score indicating good predictive performance.

---

## 🚀 How to Run This Project

1. Clone this repository
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook
4. Run `diamond_price_prediction.ipynb`

---

## 📌 Future Improvements

- Hyperparameter tuning
- Feature importance analysis
- Model deployment using Streamlit
- Add Power BI dashboard

---

## 👨‍💻 Author

Rushi Thorat  
Data Science Enthusiast  
Pune, Maharashtra  

---

⭐ If you found this project useful, feel free to give it a star!
