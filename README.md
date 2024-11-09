# 🎯 Breast Cancer Classification using Machine Learning 🚀

This project demonstrates the use of Random Forests and other machine learning techniques to classify breast tumors as benign or malignant using the well-known breast cancer dataset. The project includes data exploration, visualizations, and model evaluation to deliver accurate and interpretable results.

# 📝 Overview
Breast cancer diagnosis is a critical medical challenge, and this project leverages machine learning to improve classification accuracy. The dataset contains features derived from digitized images of fine needle aspirate (FNA) of breast masses, describing characteristics of cell nuclei.

# ✨ Key Features
- 📊 Data Exploration: Uncover patterns and relationships with EDA techniques.
- 📉 Dimensionality Reduction: PCA and t-SNE applied to visualize high-dimensional data.
- 🌟 Feature Importance: Identifying key predictors using Random Forests and statistical tests.
- 🔍 Model Training: Building a robust Random Forest classifier with cross-validation.
- 📈 Evaluation: Accuracy, confusion matrix, and classification report for model performance.
- ⚙️ Threshold Optimization: Adjusting classification thresholds to favor malignant predictions.

# 📂 Dataset
- The dataset contains 569 samples of breast tumor data.
- Each sample includes 30 numerical features such as radius, texture, perimeter, and more.
- Classes:
   - Benign (0): Non-cancerous tumors.
   - Malignant (1): Cancerous tumors.

# 🛠️ Approach
## 1. Exploratory Data Analysis
   - Visualizations like histograms, scatter plots, and heatmaps to identify patterns.
   - Statistical comparisons using T-tests to find significant features.
## 2. Dimensionality Reduction
   - PCA: Visualizing data clusters in 2D.
## 3. Feature Importance
   - Random Forest-based feature ranking to identify top predictors.
## 4. Model Building
   - Random Forest classifier trained on top features with cross-validation.
   - Threshold adjustment to improve recall for malignant cases.
## 5. Evaluation
   - Test set evaluation with accuracy, confusion matrix, and classification report.
