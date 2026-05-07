Here is a clean, text-only version of the README for your repository. 

***

# Heart Disease Prediction and Analysis

This project seeks to contribute to the detection of heart attack risk, coronary artery disease, and other cardiovascular disorders. Using the UCI Heart Disease dataset, I implemented a complete machine learning pipeline to compare the effectiveness of five different predictive models.

## Project Overview
The primary goal was to conduct an end-to-end data science workflow—from raw data cleaning to hyperparameter tuning—to determine which algorithm best predicts the occurrence of heart disease based on 13 clinical features.

### Key Features of this Repository:
* Data Cleaning: Handled over 900 clinical samples, managing missing values and converting targets into binary classification.
* Scikit-Learn Pipelines: Used to prevent data leakage by keeping preprocessing (scaling/imputation) inside the cross-validation folds.
* Hyperparameter Tuning: Optimized all models using GridSearchCV to attain maximum accuracy.
* Model Interpretability: Visualized results using PCA Decision Boundaries, Confusion Matrices, and Permutation Importance.

## Models Compared
1. K-Nearest Neighbors (KNN) - Hypothesized to perform best
2. Support Vector Machines (SVM)
3. Random Forest Classifier
4. Decision Tree Classifier
5. Logistic Regression

## Data Science Workflow
Following a systematic 10-step approach:
1. Data Collection: Using the UCI Heart Disease Dataset.
2. Data Cleaning: Removing identifiers and handling null values.
3. Normalization and Imputing: Standardizing numerical ranges and filling missing data via median/mode strategies.
4. Data Splitting: 80% Training and 20% Testing data.
5. Preliminary Analysis (EDA): Visualizing correlations and clinical patterns.
6. Feature Extraction: Identifying key predictors through importance scores.
7. Model Fitting: Training multiple classification architectures.
8. Hyperparameter Tuning: Finding optimal settings for peak performance.
9. Python Implementation: Utilizing Pandas, NumPy, Matplotlib, and Scikit-Learn.
10. Documentation: Evaluating results via classification reports and confusion matrices.

## Results Summary
After experimentation, K-Nearest Neighbors demonstrated high accuracy and reliable recall scores, proving that cardiovascular risk factors tend to form identifiable clusters in a normalized clinical space.

## Repository Structure
* heart_disease_uci.csv: The original dataset.
* main_analysis.py: The consolidated Python script for training and evaluation.
* /visualizations: Saved plots for Decision Boundaries, Feature Importance, and Confusion Matrices.

---

### How to Run
1. Clone the repository.
2. Install dependencies: pip install pandas scikit-learn matplotlib seaborn.
3. Run the script: python main_analysis.py.
