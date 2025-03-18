Iris Dataset Classification

Overview:

This project implements an end-to-end machine learning pipeline for classifying the Iris dataset. The pipeline includes data preprocessing, visualization, outlier removal, normalization, feature scaling, model training, and evaluation using multiple classifiers.

Dataset:

The dataset used is the famous Iris dataset, which consists of 150 samples of iris flowers from three different species:

Setosa

Versicolor

Virginica

Each sample has four features:

Sepal length

Sepal width

Petal length

Petal width

Features Implemented:

1. Data Preprocessing

Handling missing values

Outlier detection and removal

Feature normalization and standardization

2. Data Visualization

Histograms and box plots for feature distribution

Pair plots for feature correlation

3. Model Training

Implemented classifiers:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

k-Nearest Neighbors (KNN)

4. Model Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

Results:

After running the pipeline, the best-performing model is KNeighborsClassifier with 5 neighbors

Dependencies:

To run this project, install the required dependencies using-

pip install -r requirements.txt

How to Run the Project:

Execute the main script-

python main.py
