# codealphatask-_3
# Heart Disease Prediction using Machine Learning

## Project Overview

This project predicts the possibility of heart disease using Machine Learning classification algorithms. The model is trained on a structured medical dataset containing patient health information.

## Objective

To predict whether a patient is likely to have heart disease based on medical attributes such as age, cholesterol level, blood pressure, chest pain type, and other clinical features.

## Dataset

Dataset Used: **heart-disease.csv**

The dataset contains medical attributes and a target column:

* `target = 1` → Heart Disease Present
* `target = 0` → No Heart Disease

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Machine Learning Algorithms

The following classification algorithms are used:

1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest Classifier
4. XGBoost Classifier

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Split features and target variable.
4. Perform train-test split.
5. Apply feature scaling using StandardScaler.
6. Train multiple ML models.
7. Evaluate model performance using:

   * Accuracy Score
   * Classification Report
   * Confusion Matrix
8. Compare model results.

## Installation

Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## How to Run

1. Upload `heart-disease.csv`.
2. Open Jupyter Notebook, Kaggle Notebook, or Google Colab.
3. Run the Python code.
4. View model accuracy, classification report, and confusion matrix.

## Output

The project generates:

* Model Accuracy Scores
* Classification Report
* Confusion Matrix Visualization

## Conclusion

This project demonstrates how Machine Learning techniques can be applied to medical datasets for heart disease prediction. Different classification models are compared to identify the most effective prediction algorithm.
