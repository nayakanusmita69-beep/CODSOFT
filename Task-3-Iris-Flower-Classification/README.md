# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview

The Iris Flower Classification project is a supervised machine learning classification task that predicts the species of an Iris flower based on its sepal and petal measurements. The model is trained using the famous Iris dataset, which contains measurements of three different Iris species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), visualization, model training, evaluation, and prediction.

---

## 🎯 Objective

Develop a machine learning model that accurately classifies Iris flowers into their respective species using:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 📂 Dataset

The dataset contains **150 flower samples** with **5 columns**.

| Column | Description |
|----------|-------------|
| sepal_length | Length of the sepal (cm) |
| sepal_width | Width of the sepal (cm) |
| petal_length | Length of the petal (cm) |
| petal_width | Width of the petal (cm) |
| species | Target class |

### Species Distribution

- Iris-setosa — 50
- Iris-versicolor — 50
- Iris-virginica — 50

The dataset is balanced and contains no missing values.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset Information
- Statistical Summary
- Missing Value Analysis
- Class Distribution
- Pair Plot
- Correlation Heatmap

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Random Forest Classifier

### Workflow

1. Load Dataset
2. Explore Data
3. Data Visualization
4. Encode Target Labels
5. Split Dataset into Training & Testing Sets
6. Train Random Forest Model
7. Make Predictions
8. Evaluate Model Performance
9. Analyze Feature Importance

---

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Performance

The Random Forest model achieved an accuracy of approximately **96%–100%**, depending on the train-test split.

---

## 📌 Feature Importance

The model identified the following features as most important:

1. Petal Length
2. Petal Width
3. Sepal Length
4. Sepal Width

Petal measurements are the most significant features for distinguishing Iris species.

---

## 📁 Project Structure

```
Iris-Flower-Classification/
│
├── IRIS.csv
├── Iris_Flower_Classification.ipynb
├── README.md
├── requirements.txt
├── iris_model.pkl            (Optional)
├── feature_importance.png    (Optional)
├── confusion_matrix.png      (Optional)
└── pairplot.png              (Optional)
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
```

### Navigate to the Project

```bash
cd Iris-Flower-Classification
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook

```bash
jupyter notebook
```

Open **Iris_Flower_Classification.ipynb** and run all the cells.

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 🔮 Sample Prediction

Input:

```
Sepal Length : 5.1
Sepal Width  : 3.5
Petal Length : 1.4
Petal Width  : 0.2
```

Predicted Output:

```
Iris-setosa
```

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Label Encoding
- Classification Algorithms
- Random Forest Classifier
- Model Evaluation
- Feature Importance Analysis
- Machine Learning Workflow

---

## 📚 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Deploy using Streamlit or Flask
- Build a Web Application
- Compare multiple classification algorithms

---

## 👩‍💻 Author

**Anusmita Yogamaya Nayak**

- LinkedIn: https://www.linkedin.com/in/anusmita-yogamaya-nayak-179575334
- GitHub: https://github.com/nayakanusmita69-beep

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
