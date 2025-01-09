# breastcancerproject
This project implements a Random Forest Classifier to predict whether a breast tumor is malignant or benign using a dataset of clinical features. The model achieves a high accuracy of 96%, with an emphasis on interpretability through feature importance analysis. This work demonstrates the potential of machine learning in assisting early cancer diagnosis.

The dataset used in this project is publicly available on Kaggle: [Breast Cancer Dataset]([url](https://www.kaggle.com/datasets/rahmasleam/breast-cancer?resource=download)).
Number of Records: 569
Number of Features: 32 (including the target column diagnosis)
Target Variable:
M (Malignant): 1
B (Benign): 0

Implemented a Random Forest Classifier using Scikit-learn.
Optimized model performance through hyperparameter tuning using GridSearchCV.
Best Parameters:
n_estimators: 200
max_depth: None
min_samples_split: 2

Key predictors identified:
area_worst
concave points_worst
radius_worst
Visualized feature importance using Matplotlib and Seaborn.
