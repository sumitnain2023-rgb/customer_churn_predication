#Customer Churn Prediction
This project builds a machine learning pipeline to predict customer churn using real-world datasets from Kaggle. The model loads, analyzes, predicts, evaluates, and visualizes customer behavior to identify which customers are most likely to leave a service.

It is especially useful for telecom, banking, and SaaS platforms where customer retention is critical. By applying advanced techniques like SMOTE for imbalance handling, Logistic Regression, Decision Trees, and Random Forests, this project demonstrates how data-driven insights can reduce churn and improve business performance.

# Libraries Used
Pandas – data manipulation

Numpy – numerical computations

Matplotlib – visualization

Seaborn – statistical plots

Scikit-learn – machine learning models and evaluation

XGBOost - machine learning model 

 #Dataset
Kaggle dataset with 50,000 rows of customer records.

Includes demographic, billing, and service usage features.

Target variable: Churn (Yes/No).

 #Data Cleaning & Preprocessing
Converted categorical data into numeric using One-Hot Encoding.

Removed rows containing NaN values.

Applied SMOTE (Synthetic Minority Oversampling Technique) to balance churn vs. non-churn classes.

Split dataset into X_train, X_test, y_train, y_test for reproducible evaluation.

# Models Implemented
Logistic Regression
Baseline interpretable model.

Predictions evaluated with accuracy, precision, recall, F1-score.

Visualized results using bar charts, heatmaps, and line charts.

#Decision Tree
Captures non-linear relationships.

Evaluated with accuracy, precision, recall, F1-score.

Useful for feature importance and interpretability.

#Random Forest
Ensemble learning for higher accuracy.

Handles complex feature interactions.

Provides feature importance ranking for churn drivers.

#XGBoost (optional extension)
Gradient boosting for maximum performance.

Often achieves the best ROC-AUC on churn datasets.

#Evaluation Metrics
Accuracy: overall correctness.

Precision: how many predicted churners are correct.

Recall: ability to catch actual churners (critical for retention).

F1-score: balance between precision and recall.

ROC-AUC: measures separability of churn vs. non-churn.

#Business Impact
Helps companies reduce churn rate by identifying at-risk customers.

Enables targeted retention strategies like discounts, loyalty programs, or personalized offers.

Provides data-driven insights into customer behavior patterns.

Demonstrates end-to-end reproducible workflow for professional machine learning projects.
