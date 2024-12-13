# Gender Prediction Using Favorite Preferences

## Table of Contents

1. [Project Summary](#Project-Summary)

2. [Machine Learning Algorithms Used](#Machine-Learning-Algorithms-Used)

3. [Methodology](#Methodology)

4. [Project Files](#Project-Files)

5. [How to Run](#How-to-Run)

6. [Results](#Results)

7. [Future Work](#Future-Work)

## Project Summary

This project develops a machine learning model to predict gender based on personal preferences, including:

- Favorite Color

- Favorite Music Genre

- Favorite Beverage

- Favorite Soft Drink

The model employs supervised learning techniques, evaluating multiple classification algorithms to identify the best-performing one.

## Machine Learning Algorithms Used

The following algorithms are implemented and compared:

- Support Vector Classifier (SVC)

- k-Nearest Neighbors (KNN)

- Logistic Regression

- Random Forest Classifier

- Decision Tree Classifier

- XGBoost Classifier (XGB)

## Methodology

- Data Preprocessing:

- Conversion of categorical variables into numerical formats.

- Handling missing or inconsistent data.

- Model Training and Optimization:

- Cross-validation for robust evaluation of performance.

- Hyperparameter tuning to optimize model performance.

 **Evaluation**:

- Confusion matrix metrics (e.g., accuracy, precision, recall, F1-score) are used to analyze model predictions.

## Project Files

[ML_Gender_Prediction.ipynb](ML_Gender_Prediction.ipynb): Contains the complete implementation of the project, including data preprocessing, model training, evaluation, and results.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   
3. Open and run the Jupyter notebook:

    jupyter notebook [ML_Gender_Prediction.ipynb](ML_Gender_Prediction.ipynb)


## Results

The project identifies patterns in preferences that predict gender, with models evaluated and compared based on their performance metrics.

## Future Work

- Expand the dataset to include more diverse demographic and cultural preferences.

- Explore deep learning techniques for improved accuracy.

- Integrate additional features to enrich the prediction capabilities.

