# Bank Marketing Data Analysis and Classification

This project focuses on analyzing and predicting customer behavior based on marketing campaigns data provided by a bank. The main goal is to predict whether a customer will subscribe to a term deposit offered by the bank after being contacted through phone calls.

## Overview

The repository contains a Jupyter Notebook file named `bank.ipynb`, which demonstrates the end-to-end process of data analysis, preprocessing, and classification using machine learning algorithms. Below is a breakdown of the major steps involved:

### 1. Data Loading and Exploration

We start by cloning the repository to your local machine using Git. Once cloned, navigate to the repository directory and open the `bank.ipynb` notebook using Jupyter Notebook or any compatible environment. Execute the notebook cells sequentially to load the dataset (`bank.csv`) into a Pandas DataFrame and perform initial exploration to understand the structure and characteristics of the data.

### 2. Data Preprocessing

Before training any machine learning models, we preprocess the data by handling missing values, dropping irrelevant columns, and encoding categorical features using one-hot encoding. Additionally, we map textual month names to numerical values for better representation.

### 3. Train-Test Split

The dataset is divided into training and testing sets to evaluate the performance of the models. We use 67% of the data for training and the remaining 33% for testing.

### 4. Model Training and Evaluation

We employ three different classification algorithms for prediction:
- **Logistic Regression**: A basic linear model used for binary classification.
- **Support Vector Classifier (SVC)**: A powerful classifier that finds the optimal hyperplane to separate different classes.
- **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that classifies samples based on their similarity to neighboring samples.

### 5. Model Performance Evaluation

The performance of each model is assessed using accuracy score, which measures the proportion of correctly classified instances in the test set.

## Usage

To replicate the analysis and classification tasks performed in this project, follow these steps:
1. Clone this repository to your local machine and navigate to the cloned repository's directory using the following command:
    ```bash
    git clone https://github.com/abhiram-k-2223/bank-marketing.git
    cd bank-marketing
    ```
3. Open the `bank.ipynb` notebook using Jupyter Notebook or any compatible environment.
4. Execute each cell sequentially to reproduce the results.
