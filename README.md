🏠 House Price Prediction using Machine Learning

📌 Project Overview:

This project focuses on predicting house prices based on various property features using machine learning models. The dataset includes attributes such as area, number of bedrooms, bathrooms, stories, and amenities like air conditioning, parking, and furnishing status. The goal is to analyze the data, clean it, visualize key patterns, and build predictive models to estimate house prices accurately.

📊 Dataset Features:

The dataset contains the following columns:

• Price (Target variable) • Area • Bedrooms • Bathrooms • Stories • Mainroad • Guestroom • Basement • Hot water heating • Air conditioning • Parking • Pref area • Furnishing status

⚙️ Workflow:

Data Loading & Exploration Loaded dataset using Pandas

Checked dataset shape, structure, and missing values Identified target and feature columns

Data Cleaning Handled missing values Removed duplicate entries Converted categorical variables using one-hot encoding Prepared dataset for machine learning

Model Building Split dataset into training (80%) and testing (20%) Trained two models: Linear Regression Random Forest Regressor Evaluated models using: MAE (Mean Absolute Error) RMSE (Root Mean Squared Error) R² Score

📈 Visualization:

Three key visualizations were created:

• Distribution of house prices (Histogram)

• Correlation heatmap of features

• Actual vs Predicted price comparison

💡 Key Insights:

• Larger houses generally have higher prices

• Amenities significantly impact house value

• Non-linear models like Random Forest capture patterns better than simple regression

🛠️ Tools & Technologies:

• Python

• Pandas

• NumPy

• Matplotlib

• Scikit-learn

• Jupyter Notebook
