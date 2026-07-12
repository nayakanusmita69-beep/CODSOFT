# 🎬 Movie Rating Prediction with Python

## 📌 Project Overview

Movie Rating Prediction is a Machine Learning regression project that predicts the IMDb rating of a movie based on its characteristics such as genre, director, cast, duration, release year, and number of votes.

The project demonstrates a complete end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and prediction using Python and Scikit-learn.

---

## 🎯 Objectives

- Clean and preprocess real-world movie data.
- Perform Exploratory Data Analysis (EDA) to identify patterns and trends.
- Engineer relevant features for machine learning.
- Build a regression model to predict movie ratings.
- Evaluate model performance using multiple regression metrics.
- Save the trained model for future predictions.

---

## 📂 Dataset

**Dataset:** IMDb Movies India Dataset

### Features

- Movie Name
- Release Year
- Duration
- Genre
- Director
- Actor 1
- Actor 2
- Actor 3
- Number of Votes

**Target Variable**

- ⭐ Rating

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📊 Project Workflow

### 1️⃣ Data Collection

- Loaded IMDb Movies India dataset.

### 2️⃣ Data Cleaning

- Removed duplicate records.
- Handled missing values.
- Converted Year into numeric format.
- Converted Duration into minutes.
- Cleaned Votes column.
- Removed unnecessary characters.

### 3️⃣ Exploratory Data Analysis (EDA)

Performed detailed data visualization to understand:

- Rating Distribution
- Movie Duration Distribution
- Most Frequent Genres
- Top Directors
- Correlation Analysis
- Feature Relationships

### 4️⃣ Feature Engineering

- Handled categorical features.
- One-Hot Encoding for categorical variables.
- Median imputation for numerical values.
- Most Frequent imputation for categorical values.

### 5️⃣ Model Building

Built a Machine Learning Pipeline consisting of:

- ColumnTransformer
- SimpleImputer
- OneHotEncoder
- Random Forest Regressor

### 6️⃣ Model Evaluation

Performance evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 7️⃣ Model Saving

Saved the trained model using Joblib for future predictions.



## 📈 Machine Learning Pipeline

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Random Forest Regressor
      │
      ▼
Model Evaluation
      │
      ▼
Prediction
      │
      ▼
Model Saving

## 📊 Evaluation Metrics

The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess prediction accuracy and the model's ability to generalize to unseen data.

---

## 📷 Sample Visualizations

The project includes several visualizations such as:

- Rating Distribution
- Duration Distribution
- Top Movie Genres
- Top Directors
- Correlation Heatmap
- Actual vs Predicted Ratings
- Feature Importance

---

## 💡 Key Insights

- Movies with higher vote counts generally receive more stable ratings.
- Duration has a moderate influence on movie ratings.
- Directors and genres significantly impact predicted ratings.
- Feature engineering and proper preprocessing improve model performance.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Compare multiple regression algorithms.
- Implement XGBoost and LightGBM.
- Deploy the model using Streamlit or Flask.
- Build an interactive web application for rating prediction.

## 📌 Requirements

numpy
pandas
matplotlib
seaborn
scikit-learn
joblib

## 🎯 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Regression Modeling
- Model Evaluation
- Data Visualization
- Python Programming
- Scikit-learn Pipeline

---

## 👩‍💻 Author

**Anusmita Yogamaya Nayak**

📍 Bhubaneswar, Odisha, India

🔗 LinkedIn: https://www.linkedin.com/in/anusmita-yogamaya-nayak-179575334

💻 GitHub: https://github.com/nayakanusmita69-beep

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
