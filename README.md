# Customer Churn Prediction

![GitHub stars](https://img.shields.io/github/stars/your-username/your-repo?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/your-repo?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/your-username/your-repo?style=social)

A machine learning project to predict customer churn. This project uses a dataset of customer information to train a model that can predict whether a customer is likely to churn or not.

## Overview

This project goes through the entire machine learning workflow, from data preprocessing to model training and evaluation. The best performing model is saved and used to build a predictive system that can be used to predict churn for new customers.

## Dataset

The dataset used in this project is the "Customer Churn Dataset". It contains information about customers, including their age, gender, subscription type, and other relevant features. The dataset is split into two files:

- `customer_churn_dataset-training-master.csv`: Training data
- `customer_churn_dataset-testing-master.csv`: Testing data

## Getting Started

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

## Model Training and Results

Several models were trained and evaluated, including:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- HistGradientBoostingClassifier

The `HistGradientBoostingClassifier` was the best performing model, with a ROC AUC score of 1.0000 on the test set.

## Predictive System

The best model was saved to `best_churn_model.joblib`. A predictive system was built to predict churn for new customers. You can use the `predict_churn` function in the notebook to predict churn for a new customer.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or find any bugs.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
