# Iris_Flower_Classification

This project aims to classify Iris flowers into three species—setosa, versicolor, and virginica—using a Random Forest Classifier based on the Iris dataset. The dataset contains 150 samples with four features: sepal length, sepal width, petal length, and petal width. The goal is to build a model that accurately predicts the species from these features and generalizes well on unseen data.

The workflow begins with loading and exploring the Iris dataset using scikit-learn. No irrelevant features are removed as all four are relevant. Numerical features are scaled using StandardScaler to ensure equal contribution to the model, though this is less critical for Random Forests.

A Random Forest Classifier is trained with 100 trees (n_estimators=100, random_state=0). The model is evaluated using accuracy, confusion matrix, and classification report on a held-out test set (20% of data). Visualizations, including pair plots and correlation heatmaps, are created to understand feature relationships and model performance. 

The results show 100% accuracy with petal features being highly discriminative. Minor misclassifications occur, likely between versicolor and virginica due to feature overlap. This project demonstrates the importance of data exploration, preprocessing, and visualization in building effective classification models.

MIT License
Copyright (c) 2025 *1453nicat*
