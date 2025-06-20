
Bengaluru House Price Prediction 🏘️

📌 Overview

This project aims to predict the price of residential properties in Bengaluru using machine learning techniques. It uses a dataset containing property features such as location, square footage, number of bathrooms, and number of bedrooms. The model was developed and trained using Python in Google Colab.

🎯 Objective

The objective is to build a reliable regression model that can estimate housing prices based on input features. This can help both real estate companies and homebuyers to make informed decisions.

📁 Dataset

Source: Kaggle – Bengaluru House Price Data

Features Include:

location

total_sqft

bath

bhk

price



The dataset contains several inconsistencies and missing values, which were handled during the preprocessing stage.


🧹 Data Cleaning & Preprocessing

Removed rows with missing values

Converted non-standard square footage entries to numeric

Removed outliers based on logical constraints (e.g., unrealistic BHK/sqft ratios)

Reduced dimensionality by grouping rare locations as "other"

One-hot encoded categorical variables for model compatibility

📊 Exploratory Data Analysis (EDA)

The EDA phase included:

Distribution analysis of price vs sqft

Box plots to understand price variations per location

Scatter plots for BHK vs price analysis

Outlier detection and treatment

🧠 Model Building

Implemented multiple regression algorithms to find the best-performing model:

Linear Regression

Lasso Regression

Decision Tree Regressor

Random Forest Regressor

GridSearchCV for hyperparameter tuning

📈 Model Evaluation

Best Model: Random Forest Regressor (after tuning)

Performance Metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)

Google Colab (for cloud-based development)

Jupyter Notebook (for local testing and documentation)

📍 How to Use

1. Open the Google Colab notebook


2. Upload the dataset or connect to Google Drive


3. Run cells for data preprocessing, EDA, model training


4. Use the prediction function by entering input values like:

Location

Total square footage

Number of bedrooms (BHK)

Number of bathrooms

💡 Future Work

Deployment using Flask or Streamlit

Integrate UI for users to enter house details and get predictions

Use advanced models like XGBoost or CatBoost

Add more data from online property listings for better generalization

📬 Contact

For questions or collaborations:

Email: simhabommasani@gmail.com


