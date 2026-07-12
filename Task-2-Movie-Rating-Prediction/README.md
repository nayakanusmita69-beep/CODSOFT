# 🎬 Movie Rating Prediction using Python & Machine Learning

## 📌 Project Overview

The **Movie Rating Prediction** project is an end-to-end Machine Learning regression project that predicts IMDb movie ratings based on various movie attributes such as **genre, director, actors, release year, duration, and number of votes**.

This project demonstrates the complete Machine Learning workflow, including **data cleaning, exploratory data analysis (EDA), feature engineering, model building, evaluation, feature importance analysis, and prediction** using Python and Scikit-learn.

---

## 🎯 Objectives

- Clean and preprocess real-world movie data.
- Perform Exploratory Data Analysis (EDA) to identify trends and patterns.
- Engineer meaningful features for machine learning.
- Build a regression model to predict IMDb movie ratings.
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

### Target Variable

⭐ **Rating**

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
- Loaded the IMDb Movies India dataset.

### 2️⃣ Data Cleaning
- Removed duplicate records.
- Handled missing values.
- Converted **Year** into numeric format.
- Converted **Duration** into minutes.
- Cleaned and converted the **Votes** column.
- Removed unnecessary characters and formatted the data.

### 3️⃣ Exploratory Data Analysis (EDA)
Performed detailed visualizations to understand:

- Rating Distribution
- Duration Distribution
- Most Frequent Genres
- Top Directors
- Correlation Heatmap
- Feature Relationships

### 4️⃣ Feature Engineering
- Handled missing values.
- One-Hot Encoding for categorical variables.
- Median imputation for numerical features.
- Most Frequent imputation for categorical features.

### 5️⃣ Model Building
Built a Machine Learning Pipeline using:

- ColumnTransformer
- SimpleImputer
- OneHotEncoder
- Random Forest Regressor

### 6️⃣ Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 7️⃣ Feature Importance

- Identified the most influential features affecting movie ratings.
- Visualized feature importance using Random Forest.

### 8️⃣ Model Saving

- Saved the trained model using **Joblib** for future predictions.

---

## 📈 Machine Learning Pipeline

```text
IMDb Movie Dataset
        │
        ▼
 Data Collection
        │
        ▼
 Data Cleaning
        │
        ▼
 Exploratory Data Analysis (EDA)
        │
        ▼
 Feature Engineering
        │
        ▼
 Train-Test Split
        │
        ▼
 Data Preprocessing
(SimpleImputer + OneHotEncoder)
        │
        ▼
 Random Forest Regressor
        │
        ▼
 Model Evaluation
        │
        ▼
 Feature Importance
        │
        ▼
 Movie Rating Prediction
        │
        ▼
 Save Trained Model (.pkl)
```

---

## 📊 Evaluation Metrics

The regression model was evaluated using:

- ✅ Mean Absolute Error (MAE)
- ✅ Root Mean Squared Error (RMSE)
- ✅ R² Score

These metrics help measure prediction accuracy and the model's ability to generalize to unseen data.

---

## 📷 Project Visualizations

The project includes the following visualizations:

- Rating Distribution
- Duration Distribution
- Genre Distribution
- Top Directors
- Correlation Heatmap
- Actual vs Predicted Ratings
- Feature Importance

---

## 💡 Key Insights

- Movies with a higher number of votes generally have more reliable ratings.
- Genre and Director significantly influence movie ratings.
- Duration has a moderate impact on predicted ratings.
- Feature engineering and preprocessing improved the overall model performance.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Compare multiple regression models.
- Implement XGBoost and LightGBM.
- Deploy the model using Streamlit or Flask.
- Build an interactive Movie Rating Prediction web application.

---


## 📌 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
jupyter
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning
- Regression Modeling
- Random Forest Regression
- Feature Importance Analysis
- Model Evaluation
- Scikit-learn Pipeline
- Python Programming

---

## 👩‍💻 Author

**Anusmita Yogamaya Nayak**

📍 Bhubaneswar, Odisha, India

🔗 **LinkedIn**  
https://www.linkedin.com/in/anusmita-yogamaya-nayak-179575334

💻 **GitHub**  
https://github.com/nayakanusmita69-beep

---

## 📄 License

This project was developed for learning purposes as part of the **CodSoft Data Science Internship**.

---

⭐ **If you found this project useful, consider giving it a ⭐ on GitHub!**
