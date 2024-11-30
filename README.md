# Credit Card Fraud Detection 🛡️💳  

This project aims to detect fraudulent credit card transactions using machine learning techniques while addressing the challenges of imbalanced data.  

## 📝 Problem Statement  
Fraudulent transactions constitute a small fraction of total credit card transactions, making it a highly imbalanced classification problem. The goal is to accurately identify fraud while minimizing false positives and negatives.  

## 🔍 Steps Followed  

### Data:
Credit Card Frauds Data:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### 1️⃣ Understanding the Data  
- Explored columns and data types.  
- Described numerical and categorical features.  

### 2️⃣ Exploratory Data Analysis (EDA)  
- **Univariate Analysis:** Used histograms, distribution plots, and count plots to analyze feature distributions.  
- **Bivariate Analysis:** Investigated relationships between numerical and categorical variables using scatter, box, and violin plots.  
- **Multivariate Analysis:** Employed pair plots and correlation heatmaps for deeper insights.  

### 3️⃣ Pre-Processing  
- Handled duplicates and missing values.  
- Applied feature encoding for categorical variables (OneHotEncoder, BinaryEncoder, etc.).  
- Addressed imbalanced data using SMOTE and undersampling.  
- Scaled features using StandardScaler, MinMaxScaler, and RobustScaler.  

### 4️⃣ Modeling  
- Compared models with and without balancing techniques.  
- Optimized hyperparameters using GridSearchCV and RandomizedSearchCV.  
- Evaluated model performance using accuracy, recall, and precision.  

### ✅ Results  
- Achieved **99.9% test accuracy** with the best-performing Logistic Regression model.  
- Recall: **87%**, Precision: **65%** (focused on minimizing false negatives).  

### 5️⃣ Model Deployment  
- Saved the trained model for future use.  

## 📂 Repository Contents  
- **Dataset**: Pre-processed and cleaned data.  
- **Notebooks**: Detailed steps for EDA, pre-processing, and modeling.  
- **Results**: Performance metrics and comparisons.  
- **Saved Model**: Final Logistic Regression model.  

## 📊 Key Insights  
- Oversampling (SMOTE) significantly improved model performance.  
- Logistic Regression proved effective for this classification problem.  

---
