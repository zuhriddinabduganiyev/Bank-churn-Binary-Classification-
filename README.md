# Bank Churn Prediction

This repository contains a Jupyter Notebook `bank-churn.ipynb` that demonstrates how to build a predictive model for identifying bank customers who are likely to churn (i.e., stop using a bank's services). This notebook includes steps for data preprocessing, feature engineering, model training, and evaluation of results.

## Project Overview

Customer churn is a critical business metric in industries like banking, telecommunications, and SaaS. By predicting which customers are likely to churn, businesses can take proactive actions to retain them. In this notebook, we focus on predicting bank customer churn using machine learning techniques.

The project involves:
- Data exploration and preprocessing
- Feature scaling and engineering
- Training machine learning models (e.g., logistic regression)
- Model evaluation using metrics like ROC-AUC
- Visualization of key insights

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Features](#features)
- [Modeling](#modeling)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/zuhriddinabduganiyev/bank-churn.git
    cd bank-churn
    ```

2. Install the necessary packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

4. Open `bank-churn.ipynb` to follow along with the analysis and modeling process.

## Dataset

The dataset used in this notebook typically consists of customer records with features such as:
- Customer ID
- Account balance
- Credit score
- Geography
- Gender
- Age
- Tenure with the bank
- Number of products used
- Whether or not the customer exited (target label)

You can download the dataset from [link to dataset source, if available] or make sure it is stored in the appropriate directory when running the notebook.

## Features

The key features explored in this notebook include:
- **Demographic Data**: Age, Gender, Geography, etc.
- **Banking Data**: Credit Score, Account Balance, Number of Products, etc.
- **Target Variable**: Whether the customer churned or not (binary classification).

## Modeling

The notebook demonstrates the following steps:
1. **Data Preprocessing**:
   - Handling missing data
   - Encoding categorical variables (e.g., Gender, Geography)
   - Scaling numerical features
   
2. **Model Building**:
   - Logistic Regression with polynomial features to capture non-linear relationships.
   - Other models (if applicable, e.g., Random Forest, XGBoost).

3. **Model Evaluation**:
   - Evaluation metrics such as:
     - ROC-AUC score
     - Confusion Matrix
     - Classification Report

## Results

The notebook evaluates the model using key performance metrics and provides visualizations such as ROC curves. The model’s performance on the training and test sets is summarized using the ROC-AUC score and confusion matrix.

## Usage

After setting up the environment, you can follow the notebook step by step to:
1. Explore the data
2. Train models
3. Visualize results
4. Fine-tune models

Simply run the notebook in Jupyter and execute the cells as you go.

## Contributing

If you'd like to contribute to this project, please feel free to fork the repository and submit a pull request. We welcome all improvements and suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
