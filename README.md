# Machine Learning Laboratory — Practical 

## MSc Data Science | First Year

**Institution:** Loyola College
**Department:** Data Science
**Student Name:** HAIZEL JANANI J J
**Department Number:** 26 PDS 010

---

## About This Repository

This repository contains my Machine Learning laboratory exercises completed as part of the first-year MSc Data Science programme. It brings together practical implementations of data exploration, regression, classification, clustering, and dimensionality reduction using Python.

The notebooks are arranged in a systematic order, with code, results, evaluation metrics, and visualizations wherever applicable.

### Technologies Used

* **Python** — Programming and model implementation
* **Pandas & NumPy** — Data manipulation and numerical operations
* **Matplotlib & Seaborn** — Data visualization
* **Scikit-learn** — Machine learning algorithms and evaluation
* **Jupyter Notebook** — Practical implementation and documentation

## Practical Index

| Exercise | Practical Title                    | Dataset        |
| -------: | ---------------------------------- | -------------- |
|       01 | Exploratory Data Analysis (EDA)    | Titanic        |
|       02 | Simple Linear Regression           | Salary Dataset |
|       03 | Multiple Linear Regression         | Housing        |
|       04 | Polynomial Regression              | Fish           |
|       05 | Ridge and Lasso Regularization     | Housing        |
|       06 | Logistic Regression                | Heart Disease  |
|       07 | K-Nearest Neighbors (KNN)          | Heart Disease  |
|       08 | Decision Tree Classifier           | Heart Disease  |
|       09 | Random Forest Classifier           | Heart Disease  |
|       10 | Support Vector Machine (SVM)       | Heart Disease  |
|       11 | K-Means Clustering                 | Heart Disease  |
|       12 | Hierarchical Clustering            | Heart Disease  |
|       13 | DBSCAN Clustering                  | Heart Disease  |
|       14 | Principal Component Analysis (PCA) | Heart Disease  |

## Learning Areas

### 1. Data Exploration

Examining dataset structure, identifying missing values, understanding distributions, and discovering useful patterns through visual analysis.

### 2. Regression Models

Building regression models to understand relationships between variables and estimate continuous outcomes. This section includes linear regression, polynomial regression, and regularization methods.

### 3. Classification Algorithms

Implementing supervised learning techniques to predict categorical outcomes and evaluate model performance using suitable metrics.

### 4. Clustering Methods

Applying unsupervised learning algorithms to identify groups and patterns in data without predefined target labels.

### 5. Dimensionality Reduction

Using Principal Component Analysis to transform features into a smaller set of components while retaining as much relevant variation as possible.

## Project Organization

```text
MachineLearningLab/
│
├── dataset/
│   ├── titanic.csv
│   ├── Salary_dataset.csv
│   ├── Housing.csv
│   ├── Fish.csv
│   └── heart_disease_dataset.csv
│
├── notebooks/
│   ├── 01_eda_titanic.ipynb
│   ├── 02_simple_linear_regression.ipynb
│   ├── 03_multiple_linear_regression.ipynb
│   ├── 04_polynomial_regression_fish.ipynb
│   ├── 05_regularization_ridge_lasso.ipynb
│   ├── 06_logistic_regression.ipynb
│   ├── 07_knn_classifier.ipynb
│   ├── 08_decision_tree_classifier.ipynb
│   ├── 09_random_forest_classifier.ipynb
│   ├── 10_support_vector_machine.ipynb
│   ├── 11_kmeans_clustering.ipynb
│   ├── 12_hierarchical_clustering.ipynb
│   ├── 13_dbscan_clustering.ipynb
│   └── 14_principal_component_analysis.ipynb
│
├── optional/
├── README.md
├── requirements.txt
└── .gitignore
```

*Note: The structure above describes the intended organization. The actual folders and filenames should match the files present in the repository.*

## Setting Up the Environment

Make sure Python is installed on your system. Clone the repository and move into the project folder.

```bash
git clone https://github.com/26pds010-cloud/MachineLearningLab.git
cd MachineLearningLab
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

**Windows:**

```bash
.venv\Scripts\activate
```

**macOS/Linux:**

```bash
source .venv/bin/activate
```

Install the required packages:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the `notebooks` folder and open the practical you want to run.

## Running the Experiments

For the notebooks to run correctly:

1. Keep the datasets in the designated dataset folder.
2. Install all the dependencies listed in `requirements.txt`.
3. Execute the notebook cells in sequence.
4. Review the printed outputs, evaluation results, and graphs.
5. Save the notebook after execution if you want to retain the latest outputs.

## Repository Objectives

* Gain practical experience with fundamental machine learning algorithms.
* Understand the differences between supervised and unsupervised learning.
* Practice data preparation, feature processing, and model evaluation.
* Interpret model outputs and visualize experimental results.
* Maintain an organized record of laboratory work for academic reference.

## Conclusion

This repository serves as a practical learning record covering key machine learning concepts studied during the MSc Data Science programme. Each exercise provides an opportunity to implement algorithms, examine results, and strengthen the connection between theoretical concepts and practical applications.

---

**Course:** MSc Data Science
**Academic Level:** First Year
**Subject:** Machine Learning Laboratory
