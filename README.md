# Melanoma Skin Canceer Detection Using Machine Learning

This project implements a machine learning pipeline to classify melanoma cases based on clinical data. It provides comprehensive preprocessing, model training, validation, and performance evaluation using multiple classifiers.

Features and Workflow
🚀 Data Upload: Interactive CSV upload capability for melanoma clinical dataset.

🏷️ Label Processing: Automatic or manual detection of the binary target column ensuring numeric encoding (benign vs. malignant).

🧹 Preprocessing Pipeline:

Separates numerical and categorical features.

Handles missing values with median imputation for numerics and most frequent value for categoricals.

Applies standard scaling to numerical columns.

Uses one-hot encoding for categorical columns.

🤖 Models Compared:

Logistic Regression with balanced class weights.

Random Forest Classifier with 400 trees and class balancing.

Support Vector Machine (RBF kernel) with probabilistic outputs and class balancing.

K-Nearest Neighbors with 5 neighbors.

🔄 Cross-Validation: Stratified 5-fold cross-validation to maintain balanced class distributions in training and validation folds.

📊 Performance Metrics:

Accuracy

Precision

Recall (Sensitivity)

Specificity (custom defined)

F1-Score

ROC AUC

Metrics include mean and standard deviation across folds for robustness.

📈 Visualization:

Comparative bar charts for model performance metrics.

Confusion matrix heatmaps for visualizing classification errors.

🎯 Final Training:

Best models retrained on the entire dataset.

Overall confusion matrices displayed for conclusive evaluation.

This notebook is designed to be reproducible and extensible for clinical classification tasks on structured datasets, offering a clean and modern approach to machine learning model evaluation.
