# Customer-Churn-Prediction-using-Machine-Learning
Machine learning project to predict customer churn using Telco data. Implemented full pipeline including preprocessing, feature encoding, scaling, and model training. Compared multiple classification models and evaluated using precision, recall, and accuracy. Optimized model performance with focus on churn recall for business impact.

1. Data Understanding:
We first explored the dataset to understand structure, feature types, and identify the target variable (Churn). This helps define the problem clearly before modeling.

2. Data Preprocessing:
We cleaned missing values and converted categorical data into numerical format because machine learning models cannot directly process text data.

3. Feature Engineering:
We applied encoding and scaling to ensure all features are in a machine-readable format and equally weighted. This prevents bias caused by large numerical ranges.

4. Model Training:
We trained multiple classification models (Logistic Regression, Decision Tree, Random Forest) to compare performance and select the best approach.

5. Model Evaluation:
We used accuracy, precision, recall, and confusion matrix. Recall was prioritized because correctly identifying churned customers is more important than overall accuracy.

6. Final Decision:
Logistic Regression was selected because it provided the best balance with highest recall, making it most useful for real-world business retention strategies.
