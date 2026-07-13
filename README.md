# 🏠 House Price Prediction using Machine Learning

A machine learning project that predicts house prices based on property characteristics and amenities. The project includes data preprocessing, exploratory data analysis, model building, performance evaluation, and business insights to understand the factors that influence housing prices.

---

## 📌 Overview

Accurately estimating house prices is valuable for buyers, sellers, and real estate professionals. This project analyzes housing data to identify the factors affecting property prices and builds machine learning models capable of predicting house values based on property features.

The project emphasizes both predictive performance and interpretability, helping users understand which property characteristics contribute most to house prices.

---

## 📂 Dataset

The dataset contains residential property information with the following features:

### **Target Variable**
- **Price**

### **Features**
- Area
- Bedrooms
- Bathrooms
- Stories
- Mainroad
- Guestroom
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

The dataset contains a mix of numerical and categorical variables.

---

## 🚀 Project Workflow

### 1. Data Loading & Exploration

- Loaded the dataset using Pandas
- Inspected dataset shape and structure
- Checked data types
- Identified missing values
- Explored feature distributions
- Defined target and predictor variables

---

### 2. Data Cleaning & Preprocessing

- Handled missing values
- Removed duplicate records
- Applied One-Hot Encoding to categorical variables
- Prepared the dataset for machine learning
- Split features and target variable

---

### 3. Exploratory Data Analysis (EDA)

Performed data analysis to better understand relationships between property features and house prices, including:

- Distribution of house prices
- Correlation among numerical features
- Relationship between area and price
- Effect of amenities on house prices
- Feature importance through correlation analysis

---

### 4. Model Building

The dataset was divided into:

- **Training:** 80%
- **Testing:** 20%

Two regression models were trained and compared:

- Linear Regression
- Random Forest Regressor

---

### 5. Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Performance metrics were compared to identify the model with the highest predictive accuracy.

---

### 6. Visualizations

The project includes:

- 📊 House Price Distribution (Histogram)
- 🔥 Feature Correlation Heatmap
- 📈 Actual vs Predicted House Prices

---

## 📊 Key Insights

- Larger houses generally command higher market prices.
- Properties with additional amenities such as air conditioning, parking, and preferred locations tend to have higher values.
- The number of bathrooms and overall living area are among the strongest indicators of price.
- Random Forest captures complex, non-linear relationships more effectively than Linear Regression, resulting in improved prediction accuracy.

---

## 💡 Applications

- Estimate house prices based on property features.
- Support real estate investment decisions.
- Assist buyers and sellers with property valuation.
- Provide insights into the factors that influence housing prices.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── data/
│   └── Housing.csv
│
├── notebooks/
│   └── House_Price_Prediction.ipynb
│
├── images/
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   └── actual_vs_predicted.png
│
├── README.md
└── requirements.txt
```

---

## 🎯 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Experiment with XGBoost, LightGBM, and CatBoost
- Perform feature selection and engineering
- Deploy the model as a Streamlit web application
- Add SHAP values for model explainability
- Build an interactive dashboard for house price prediction

---

## 👨‍💻 Author

**Raihan Valiyakath Mohamed**

- B.Tech Computer Science & Business Systems (CSBS)
- Python | Machine Learning | Data Analytics | AI
