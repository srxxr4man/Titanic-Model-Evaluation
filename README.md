# 🚢 Titanic Model Evaluation

## About
A Machine Learning project using the Titanic dataset to predict passenger survival and evaluate the performance of different classification algorithms.

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Algorithms Implemented
- K-Nearest Neighbors (KNN)
- Logistic Regression

## Project Workflow
- Loading the Titanic dataset.
- Handling missing values.
- Encoding categorical features.
- Feature scaling using StandardScaler.
- Training classification models.
- Comparing training and testing accuracy.
- Evaluating different K values in KNN (K = 1 to 29).
- Predicting passenger survival using unseen data.

## Model Evaluation Results

| Model | Testing Accuracy |
|---|---:|
| KNN (K=1) | 79.27% |
| KNN (K=3) | 83.75% |
| KNN (K=5) | 83.47% |
| Logistic Regression | 83.47% |
| KNN (K=26) | 84.03% |

**Best observed accuracy: 84.03% (KNN, K=26).**

## Project Structure

```text
Titanic-Model-Evaluation/
├── Model_Evaluation_Titanic_Dataset.ipynb
└── README.md
```

## How to Run
1. Download the `.ipynb` file from this repository.
2. Open it using Jupyter Notebook or Google Colab.
3. Run the cells sequentially.

## Key Learnings
- Data preprocessing and feature scaling.
- Understanding classification algorithms.
- Model performance evaluation.
- Comparing different K values.
- Understanding overfitting and generalization.

---

**Category:** Machine Learning | Classification | Model Evaluation
