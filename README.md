# ⚙️ End-to-End Machine Learning Pipeline

A comprehensive, structured Machine Learning pipeline demonstrating a full workflow from raw data to a tuned, deployable model. This project tackles both **Regression** and **Classification** tasks using standard Scikit-Learn libraries.

## 📂 Project Overview

This notebook serves as a practical implementation of core ML concepts, proving proficiency in data handling, exploratory data analysis (EDA), model selection, and hyperparameter tuning.

### 1️⃣ Regression Task (California Housing Dataset)
* **Goal:** Predict median house prices based on various features.
* **Models Trained & Compared:** Linear Regression, Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Regression (SVR).
* **Evaluation Metrics:** RMSE (Root Mean Squared Error) and R² Score.

### 2️⃣ Classification Task (Iris Dataset)
* **Goal:** Classify iris flower species.
* **Models Trained & Compared:** Logistic Regression, Decision Tree, Random Forest, KNN, and Support Vector Classifier (SVC).
* **Evaluation Metrics:** Accuracy, Precision, Recall, and F1-Score.

## 🛠️ Key Techniques Demonstrated
* **Data Preprocessing:** Handling missing values, Feature Scaling using `StandardScaler`, and Train/Test splitting.
* **Exploratory Data Analysis (EDA):** Visualizing target distributions and feature correlation using Seaborn heatmaps.
* **Model Evaluation:** Implementing advanced visualization techniques such as **Confusion Matrix** plots for classification performance.
* **Feature Importance:** Extracting and plotting the most influential features using Random Forest to provide model explainability.
* **Hyperparameter Tuning:** Utilizing `GridSearchCV` to systematically find the optimal parameters (e.g., `n_estimators`, `max_depth`) for the Random Forest model.
* **Model Deployment Prep:** Saving the final optimized model using `joblib` for future inference.

## 📊 Visualizations & Outputs
*(Key insights and model evaluation metrics extracted from the pipeline)*

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <img src="image (1).png" width="48%" alt="Data Visualization 1" style="margin-bottom: 10px;">
  <img src="image (2).png" width="48%" alt="Data Visualization 2" style="margin-bottom: 10px;">
  <img src="image (3).png" width="48%" alt="Data Visualization 3" style="margin-bottom: 10px;">
  <img src="image (4).png" width="48%" alt="Data Visualization 4" style="margin-bottom: 10px;">
</div>

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`

## 👨‍💻 About the Author
**Ahmed Saeed Abdullah Alshanwany**
AI & Computer Science Student | Passionate about building robust Machine Learning pipelines and data-driven solutions.
