# 🚀 Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A machine learning project to predict customer churn using a dataset of customer information. This project aims to build a reliable predictive system to identify customers who are likely to churn.

## ✨ Features

*   **Data Preprocessing**: Cleaning and preparing the data for modeling.
*   **Exploratory Data Analysis (EDA)**: Visualizing the data to uncover insights.
*   **Model Training**: Training multiple machine learning models to find the best performer.
*   **Model Evaluation**: Evaluating the models using various metrics.
*   **Predictive System**: A simple system to predict churn for new customers.

## 📊 Dataset

The dataset used in this project is the "Customer Churn Dataset". It contains information about customers, including their age, gender, subscription type, and other relevant features. The dataset is split into two files:

*   `customer_churn_dataset-training-master.csv`: Training data
*   `customer_churn_dataset-testing-master.csv`: Testing data

## 🤖 Machine Learning Workflow

This project follows a standard machine learning workflow:

1.  **Data Loading and Initial Exploration**: The datasets are loaded, and an initial analysis is performed to understand the data's structure and features.
2.  **Data Preprocessing and Feature Engineering**: The data is cleaned, missing values are handled, and categorical features are encoded.
3.  **Model Training**: Several classification models are trained on the preprocessed data.
4.  **Model Evaluation**: The trained models are evaluated using cross-validation and various performance metrics, with a focus on ROC AUC.
5.  **Hyperparameter Tuning**: The best-performing model is selected for further tuning to optimize its performance.
6.  **Final Model Training and Saving**: The final model is trained on the entire training dataset and saved for future use in a predictive system.

## 🏆 Model Performance

Several models were trained and evaluated. The `HistGradientBoostingClassifier` was the best performing model.

| Model | Mean ROC AUC |
| :--- | :--- |
| Logistic Regression | 0.8934 |
| Random Forest | 1.0000 |
| Gradient Boosting | 0.9999 |
| **HistGradientBoostingClassifier** | **1.0000** |

The `HistGradientBoostingClassifier` achieved a perfect ROC AUC score of 1.0000 on the test set.

## 🛠️ Getting Started

### Prerequisites

*   Python 3.10 or higher
*   Jupyter Notebook or JupyterLab

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```
2.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1.  Open the Jupyter notebook `customer_churk.ipynb` to see the code for data preprocessing, model training, and evaluation.
2.  To use the predictive system, you can use the `predict_churn` function in the notebook.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or find any bugs.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.