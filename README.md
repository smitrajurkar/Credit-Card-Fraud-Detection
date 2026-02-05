Project Overview:
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.The goal is to build a predictive model that can accurately identify fraud transactions and minimize financial loss.Credit card fraud detection is a highly imbalanced classification problem where fraudulent transactions are very rare compared to normal transactions. This project applies data preprocessing, feature engineering, and machine learning algorithms to detect fraud effectively.

Objectives:
Detect fraudulent transactions from credit card data
Handle imbalanced dataset using advanced techniques
Build and evaluate machine learning models
Improve model accuracy and precision for fraud detection

Technologies Used:
Python
Jupyter Notebook
Pandas & NumPy – Data processing
Matplotlib & Seaborn – Data visualization
Scikit-learn – Machine Learning models

Dataset:
The dataset contains anonymized credit card transactions with features such as:
Time
Amount
PCA-transformed features (V1–V28)
Class (0 = Normal, 1 = Fraud)
This is an imbalanced dataset where fraud cases are very low compared to normal transactions.

📊 Project Workflow:

1️⃣ Data Collection
Loaded dataset using Pandas
Explored structure and features

2️⃣ Data Preprocessing
Checked missing values
Handled imbalanced data
Scaled transaction amount and time

3️⃣ Exploratory Data Analysis (EDA)
Visualized fraud vs normal transactions
Analyzed transaction patterns
Correlation heatmap

4️⃣ Model Building
Machine learning models used:
Logistic Regression
Decision Tree
Random Forest

5️⃣ Model Evaluation
Evaluation metrics:
Accuracy Score
Precision
Recall
F1 Score
Confusion Matrix
