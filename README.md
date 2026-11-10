# 🚢 Titanic Dataset — Machine Learning & Model Evaluation

<p align="center">
  <b>Explore Data. Train Models. Evaluate Performance. Predict Survival.</b>
  <br>
  A beginner-friendly Machine Learning project exploring classification algorithms using the Titanic passenger dataset.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/ML-Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Environment-Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Machine%20Learning-green?style=for-the-badge" />
</p>

---

## 📌 About the Project

This repository contains two Jupyter Notebooks that explore the **Titanic dataset** and demonstrate the application of Machine Learning classification algorithms to predict passenger survival.

The project focuses on understanding the fundamentals of Machine Learning through dataset exploration, data preprocessing, feature selection, supervised learning, model training, and performance evaluation using Python and Scikit-learn.

Two classification algorithms, **K-Nearest Neighbors (KNN)** and **Logistic Regression**, are implemented and evaluated to understand their performance on the Titanic dataset.

## ✨ Key Features

- 📊 **Dataset Exploration:** Load, inspect, and understand the Titanic passenger dataset.
- 🔍 **Data Analysis:** Identify observations, features, and target variables.
- 🧹 **Data Preprocessing:** Handle missing values and prepare data for model training.
- 🔤 **Categorical Encoding:** Convert categorical features into numerical representations.
- 📐 **Feature Scaling:** Apply StandardScaler to standardize numerical features.
- 🤖 **Machine Learning Models:** Implement KNN and Logistic Regression.
- 📈 **Model Evaluation:** Compare training and testing accuracy.
- 🔄 **Hyperparameter Experimentation:** Evaluate KNN with different K values from 1 to 29.
- 📉 **Data Visualization:** Plot the relationship between K values and testing accuracy.
- 🔮 **Survival Prediction:** Predict passenger survival using unseen passenger data.

## 🚀 Notebooks Included

### 1. 📘 Getting Started with Titanic Dataset

**File:** `Getting_Started_with_Titanic_Dataset.ipynb`

An introductory notebook focused on understanding the Titanic dataset and preparing the data for Machine Learning.

**Topics Covered:**
- Introduction to the Titanic dataset.
- Loading and inspecting datasets using Pandas and Seaborn.
- Understanding observations, features, and target variables.
- Introduction to supervised learning.
- Understanding binary classification.
- Selecting relevant features.
- Separating input variables (`X`) and target variable (`y`).
- Preparing numerical data for Scikit-learn.

### 2. 📊 Model Evaluation — Titanic Dataset

**File:** `Model_Evaluation_Titanic_Dataset.ipynb`

A practical notebook that implements classification algorithms and evaluates their performance in predicting passenger survival.

**Topics Covered:**
- Data preprocessing and handling missing values.
- Encoding categorical variables.
- Feature scaling using `StandardScaler`.
- Implementing K-Nearest Neighbors (KNN).
- Implementing Logistic Regression.
- Comparing training and testing accuracy.
- Experimenting with K values from 1 to 29.
- Visualizing K values against testing accuracy.
- Making predictions on unseen passenger data.

## 🧠 Machine Learning Algorithms

### 1. K-Nearest Neighbors (KNN)

KNN is a supervised Machine Learning algorithm that predicts the class of a data point based on the classes of its nearest neighbors.

In this project:
- Different K values are tested.
- Passenger survival is predicted based on neighboring data points.
- Testing accuracy is compared to identify the best observed K value.

### 2. Logistic Regression

Logistic Regression is a supervised classification algorithm used to predict the probability of an outcome.

In this project:
- The model learns relationships between passenger features and survival.
- It performs binary classification.
- Its performance is compared with KNN using testing accuracy.

## 📊 Model Evaluation Results

The following results were obtained using a **60:40 training-testing split** with `random_state=4`.

| Model | Testing Accuracy |
|---|---:|
| KNN (K=1) | 79.27% |
| KNN (K=3) | 83.75% |
| KNN (K=5) | 83.47% |
| Logistic Regression | 83.47% |
| KNN (K=26) | **84.03%** |

<badge color="success">Best observed accuracy: 84.03%</badge>

**Observation:** KNN with K=26 achieved the highest testing accuracy among the reported experiments.

*Note: These results are based on a single train-test split. K-fold cross-validation can provide a more reliable estimate of model performance and help with model selection.*

## 🔄 Machine Learning Workflow

```text
          START
            |
            v
    Load Titanic Dataset
            |
            v
      Data Exploration
            |
            v
     Feature Selection
            |
            v
    Data Preprocessing
            |
            v
   Handle Missing Values
            |
            v
  Encode Categorical Data
            |
            v
     Feature Scaling
            |
            v
    Train-Test Splitting
            |
            v
     Model Training
       /        \
      v          v
     KNN    Logistic Regression
      \          /
       v        v
      Model Evaluation
            |
            v
    Compare Accuracy
            |
            v
   Predict Passenger Survival
            |
            v
           END
```

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| 🐍 Python | Core programming language |
| 🐼 Pandas | Data manipulation and analysis |
| 🔢 NumPy | Numerical computations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical data visualization |
| 🤖 Scikit-learn | Machine Learning model implementation and evaluation |
| 📓 Jupyter Notebook | Interactive development environment |

## 🏗️ Project Structure

```text
Titanic-Model-Evaluation/
│
├── Getting_Started_with_Titanic_Dataset.ipynb
│
├── Model_Evaluation_Titanic_Dataset.ipynb
│
└── README.md
```

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Titanic-Model-Evaluation.git
```

### 2. Navigate to the Project Directory

```bash
cd Titanic-Model-Evaluation
```

### 3. Install Required Libraries

```bash
pip install pandas numpy seaborn matplotlib scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Execute the Notebooks

Open and run the notebooks in the following order:

1. `Getting_Started_with_Titanic_Dataset.ipynb`
2. `Model_Evaluation_Titanic_Dataset.ipynb`

Run the cells sequentially to explore the dataset, train classification models, and understand their performance.

## 🎯 Project Objectives & Learning Outcomes

This project focuses on developing a practical understanding of Machine Learning fundamentals through a real-world dataset.

**Key Learning Outcomes:**

- Understanding structured datasets and their features.
- Learning the fundamentals of supervised Machine Learning.
- Understanding binary classification problems.
- Performing data preprocessing and feature selection.
- Handling missing values and categorical variables.
- Applying feature scaling techniques.
- Implementing KNN and Logistic Regression.
- Evaluating models using training and testing accuracy.
- Understanding the impact of hyperparameters on model performance.
- Exploring overfitting and generalization.
- Making predictions using trained Machine Learning models.

## 🔮 Future Enhancements

- 📊 Include confusion matrix and classification reports.
- 📈 Evaluate models using precision, recall, and F1-score.
- 🔄 Implement K-fold cross-validation.
- ⚙️ Apply GridSearchCV for hyperparameter tuning.
- 🌳 Experiment with Decision Tree and Random Forest classifiers.
- 📉 Compare additional classification algorithms.
- 🎨 Develop an interactive survival prediction dashboard using Streamlit.

## 🎓 Academic Project Details

| Detail | Information |
|---|---|
| **Institution** | Muthoot Institute of Technology and Science (MITS) |
| **Department** | Artificial Intelligence and Data Science |
| **Academic Batch** | 2025–2029 |
| **Project Domain** | Machine Learning & Data Analysis |
| **Project Title** | Titanic Dataset — Machine Learning & Model Evaluation |
| **Project Type** | Practical Learning / Academic Project |
| **Programming Language** | Python |

## 👨‍💻 Author

<p align="center">
  <b>A Sreeram</b>
  <br>
  Artificial Intelligence & Data Science Student
  <br>
  Muthoot Institute of Technology and Science (MITS)
  <br><br>
  💡 Interested in Machine Learning, Python, Data Science and AI.
</p>

---

<p align="center">
  <b>🚢 Turning Historical Data into Machine Learning Insights.</b>
  <br><br>
  ⭐ If you find this project interesting, consider giving this repository a star!
  <br><br>
  <b>Made with ❤️, Python and Machine Learning.</b>
</p>
