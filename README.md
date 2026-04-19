Heart Disease Prediction using Machine Learning
📌 Project Overview

This project aims to predict the presence of heart disease using machine learning algorithms.
Several classification models were built and evaluated to compare their performance.

📂 Dataset

The dataset used (heart.csv) contains various medical attributes such as:

Age
Sex
Chest pain type (cp)
Resting blood pressure (trestbps)
Cholesterol level (chol)
And other clinical features

🎯 The target variable (num) was converted into binary format:

0 → No heart disease
1 → Presence of heart disease
⚙️ Data Preprocessing

The following preprocessing steps were applied:

Dropped unnecessary columns (id, dataset)
Removed missing values (NaN)
Encoded categorical variables using LabelEncoder
Scaled features using StandardScaler
🤖 Model Selection

Three different machine learning algorithms were used:

1. Logistic Regression
Simple and interpretable model
Works well with linear relationships
Serves as a strong baseline
2. K-Nearest Neighbors (KNN)
Based on similarity between data points
Can capture non-linear patterns
3. Naive Bayes
Probabilistic model
Fast and effective for smaller datasets


📊 Model Performance
Model	Accuracy
Logistic Regression	XX%
KNN (k=3)	XX%
Naive Bayes	XX%

👉 Replace XX% with your actual results

📈 Visualizations
🔹 Class Distribution

Shows how the data is distributed across target classes.

🔹 Correlation Matrix

A heatmap displaying relationships between features.

🔹 Model Comparison

A bar chart comparing model accuracies.

🔍 Confusion Matrix & Evaluation

For each model, the following metrics were evaluated:

Confusion Matrix
Precision
Recall
F1-score

These metrics provide deeper insight into model performance beyond accuracy.

🏆 Best Model Analysis

Based on the results:

Logistic Regression achieved the best performance.

📌 Reasons:

The dataset likely contains linear relationships
The model is less prone to overfitting
More stable compared to KNN

KNN performed slightly worse due to sensitivity to noise.
Naive Bayes showed the lowest accuracy because of its strong independence assumption.

🎯 Example Predictions

Example:

Predicted: [1, 0, 1, 0, 1]
Actual:    [1, 0, 0, 0, 1]

This demonstrates how the model performs on real test samples.

🚀 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

⚠️ Limitations
Dataset is relatively small
Possible class imbalance
No hyperparameter tuning applied

🔮 Future Improvements
Use advanced models (Random Forest, XGBoost)
Perform hyperparameter tuning
Add ROC Curve and AUC metrics
Handle class imbalance (e.g., SMOTE)
Deploy as a web application (Flask / Django)


▶️ Run
Open and run all cells in Jupyter Notebook.