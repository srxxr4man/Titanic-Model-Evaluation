# 🚢 Titanic Dataset – Machine Learning & Model Evaluation

## About

This repository contains two Jupyter Notebooks that explore the Titanic dataset and demonstrate the application of Machine Learning classification algorithms to predict passenger survival.

The project covers the basics of dataset exploration, data preprocessing, supervised learning, model training, and performance evaluation using Python and Scikit-learn.

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Notebooks Included

### 1. Getting Started with Titanic Dataset

**File:** `Getting_Started_with_Titanic_Dataset.ipynb`

An introductory notebook focused on understanding the Titanic dataset and preparing data for Machine Learning.

Topics covered:
- Introduction to the Titanic dataset.
- Loading and inspecting data using Pandas and Seaborn.
- Understanding observations, features, and target variables.
- Introduction to supervised learning and binary classification.
- Selecting features and separating input variables (X) and target variable (y).
- Preparing numeric data for Scikit-learn.

### 2. Model Evaluation – Titanic Dataset

**File:** `Model_Evaluation_Titanic_Dataset.ipynb`

A practical notebook that builds and evaluates classification models to predict passenger survival.

Topics covered:
- Data preprocessing and handling missing values.
- Encoding categorical variables.
- Feature scaling using StandardScaler.
- Training and evaluating K-Nearest Neighbors (KNN).
- Implementing Logistic Regression.
- Comparing training and testing accuracy.
- Experimenting with different K values (K = 1 to 29).
- Visualizing the relationship between K values and testing accuracy.
- Making predictions on unseen passenger data.

## Algorithms Implemented

- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**

## Model Evaluation Results

The following results were obtained using a 60:40 train-test split with `random_state=4`.

| Model | Testing Accuracy |
|---|---:|
| KNN (K=1) | 79.27% |
| KNN (K=3) | 83.75% |
| KNN (K=5) | 83.47% |
| Logistic Regression | 83.47% |
| KNN (K=26) | 84.03% |

**Best observed testing accuracy: 84.03% using KNN (K=26).**

*Note: These results are based on a single train-test split. K-fold cross-validation would provide a more reliable estimate for model selection.*

## Project Workflow

1. Explore and understand the Titanic dataset.
2. Identify features and the target variable.
3. Preprocess the data and handle missing values.
4. Encode categorical variables and scale numerical features.
5. Split the dataset into training and testing sets.
6. Train KNN and Logistic Regression models.
7. Evaluate and compare model performance.
8. Experiment with different K values to identify the best observed result.
9. Use the trained model to predict survival for unseen passenger data.

## Project Structure

```text
Titanic-Model-Evaluation/
│
├── Getting_Started_with_Titanic_Dataset.ipynb
├── Model_Evaluation_Titanic_Dataset.ipynb
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Open the repository folder in Jupyter Notebook or Visual Studio Code.
3. Install the required Python libraries if they are not already installed.
4. Open the notebooks in the following order:
   - `Getting_Started_with_Titanic_Dataset.ipynb`
   - `Model_Evaluation_Titanic_Dataset.ipynb`
5. Run the cells sequentially to explore the dataset and understand the model evaluation process.

## Key Learnings

- Understanding real-world tabular datasets.
- Basics of supervised Machine Learning.
- Data preprocessing and feature selection.
- Handling missing values and categorical data.
- Implementing classification algorithms.
- Evaluating model performance using training and testing accuracy.
- Understanding the effect of model parameters on performance.
- Exploring overfitting and generalization.

---

**Category:** Machine Learning | Python | Classification | Model Evaluation
