# Stroke Prediction: A Machine Learning Approach
Project Overview
This project aims to predict the probability of a stroke based on clinical and lifestyle parameters such as gender, age, hypertension, heart disease, smoking status, and glucose levels.

The dataset is highly imbalanced (only ~4.87% of samples recorded a stroke), presenting a significant challenge for model accuracy.

Key Methodologies
1. Data Preprocessing & Feature Engineering
Handling missing values and encoding categorical variables.

Addressing data imbalance using SMOTE (Synthetic Minority Over-sampling Technique) to improve model sensitivity.

2. Supervised Learning
Neural Networks: Developed using TensorFlow/Keras, implementing Dropout layers to prevent overfitting and Early Stopping for optimization.

Logistic Regression: Used as a baseline model to identify key features increasing or decreasing stroke risk.

3. Unsupervised Learning
K-Means Clustering: Segmenting the population into risk clusters.

Dimensionality Reduction: Using PCA, Isomap, and UMAP to visualize complex data structures and identify patterns in stroke occurrences.

Technologies Used
Language: Python

DL/ML: TensorFlow, Keras, Scikit-learn, Imbalanced-learn (SMOTE)

Data Handling: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Results & Insights
The models successfully identified high-risk groups despite the initial data imbalance.

Dimensionality reduction (Isomap/UMAP) clearly showed clustering of stroke patients in specific data regions, confirming the importance of feature selection.

Data Source: Kaggle Stroke Prediction Dataset
