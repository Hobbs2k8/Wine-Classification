# Wine Quality Classification using Random Forest and SMOTE
This project demonstrates a machine learning pipeline for classifying the quality of red wine based on its physicochemical properties. The dataset is sourced from the UCI Machine Learning Repository, specifically the Wine Quality dataset.

Key Steps:

Data Preprocessing:
Handled class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
Standardized the features using StandardScaler.

Modeling:
Trained a Random Forest Classifier with hyperparameters fine-tuned to optimize performance.
Achieved an accuracy of 84.8% on the test set.

Evaluation:
Provided a detailed classification report showcasing precision, recall, and F1-score for each class.
Visualized the Top 10 Feature Importances to understand which features contributed the most to the predictions.
Plotted a Confusion Matrix to analyze the model's performance across different classes.

Dependencies:
!pip install pandas scikit-learn matplotlib seaborn imbalanced-learn

Usage:
To run the code in your own environment, simply clone this repository and open the notebook in Google Colab using the Open in Colab button above.

