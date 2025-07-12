# Proj_05_Breast_Cancer_SVM

This project is based on the Breast Cancer Wisconsin (Diagnostic) Dataset, which contains 30 features computed from digitized images of breast mass cell nuclei. The aim is to classify tumors as malignant or benign using Support Vector Machine (SVM) classifiers with different kernels (Linear, RBF, Polynomial, Sigmoid).

Purpose
To make the diagnosis of breast cancer more accurate and faster using machine learning.

To compare the performance of different SVM kernels on this dataset and identify the best-performing kernel.

Features
Dataset: Breast Cancer Wisconsin (Diagnostic) (569 samples, 30 features, 2 classes: malignant, benign)

Data Preprocessing: Feature scaling using StandardScaler

Models: SVM with Linear, RBF, Polynomial, and Sigmoid kernels

Evaluation: Accuracy Score and Confusion Matrix Visualization for each kernel

Usage Instructions
Install Required Libraries:

pip install scikit-learn matplotlib

Run the Code:

The code loads the Breast Cancer dataset from sklearn.

Data is scaled so all features have equal importance.

The dataset is split into training (75%) and testing (25%) sets.

Four different SVM kernels are used to train and test the models.

For each model, the accuracy score and confusion matrix are displayed.

View Results:

Accuracy and confusion matrix are printed for each kernel.

The confusion matrix is also visualized using ConfusionMatrixDisplay.
