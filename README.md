# Breast Cancer Detection with Machine Learning

This repository implements a machine learning approach to classify breast cancer data.

## Key Features:

- Utilizes various machine learning algorithms for breast cancer classification: Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machines (SVM) with linear and RBF kernels, Naive Bayes, and Decision Tree.
- Employs data preprocessing techniques:
- Loads data from a CSV file (`Breast_Cancer_Dataset.csv`).
- Splits data into training and testing sets for model evaluation.
- Performs feature scaling for improved model performance.
- Trains and evaluates each model on the prepared data.
- Compares the performance of different models using accuracy scores and visualizes confusion matrices for better understanding of classification results.
- Plots bar charts and error bar charts to depict model accuracy and their variances.

## Libraries Used:

* pandas
* numpy
* matplotlib.pyplot
* seaborn
* sklearn (various submodules for model training and evaluation)

## How to Use:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ar-archith/Breast-Cancer-Detection.git

2. Ensure Data File:
   The script assumes a CSV file named `Breast_Cancer_Dataset.csv` exists in the same directory. This file should contain features for breast cancer classification and a target variable indicating the presence or absence of cancer.

3. Run the Script:
   Open the `Breast_Cancer_Detection.ipynb` file in your preferred Jupyter Notebook environment and execute the code cells.

## Evaluation and Results:

The script trains and compares the performance of various machine learning models. The results include:
- Accuracy scores for each model on the test set.
- Confusion matrices for better understanding of true positives, false positives, true negatives, and false negatives.
- Bar charts and error bar charts to visualize model accuracy comparisons.

## Disclaimer:

This is a basic example using a limited set of machine learning algorithms. Real-world breast cancer diagnosis relies on medical expertise and various tests. This project serves as an educational demonstration of machine learning applications in healthcare data analysis.
