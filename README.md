Description

  The Car Evaluation Prediction project aims to develop a machine learning pipeline that predicts car evaluations based on features like price, safety, and capacity. Using a dataset from the UCI Machine Learning Repository, the project applies various preprocessing techniques, exploratory data analysis (EDA), and machine learning models to classify cars into different evaluation categories.

This project demonstrates feature encoding, scaling, and hyperparameter tuning, and evaluates the performance of Logistic Regression, Decision Tree, and Random Forest classifiers.

Project Workflow

1. Data Exploration and Preprocessing
Loaded and analyzed the dataset using the ucimlrepo package.
Explored feature distributions, unique values, and handled missing/null values.
Encoded categorical features using LabelEncoder.
Scaled features using StandardScaler for better model performance.
2. Model Training
Three models were trained on the dataset:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
3. Model Evaluation
Models were evaluated using:

Classification Report (Precision, Recall, F1 Score)
Accuracy Score
Confusion Matrix
ROC-AUC Curve
4. Hyperparameter Tuning
Used RandomizedSearchCV with cross-validation to optimize hyperparameters for the Random Forest model.
