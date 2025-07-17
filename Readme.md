# 🧠 Credit Score Modeling and Wallet Segmentation

This project involves clustering customer wallets based on behavioral and financial features, and assigning each wallet a credit score (ranging from 0 to 1000) using regression-based machine learning models.

---

## 🚀 Workflow

### 1. Load the JSON data  
Parse the raw data and load it for analysis.

### 2. Convert to Pandas DataFrame (Preprocessing)  
Clean and normalize the structure for further processing.

### 3. Feature Engineering  
Derive meaningful features relevant to credit scoring.

### 4. Exploratory Data Analysis (EDA)  
Visualize and understand trends, patterns, and distributions.

### 5. Model Training  
Train and evaluate various regression models to predict credit scores.

### 6. Feature Importance  
Analyze which features contribute most to the credit score prediction.

### 7. Cluster Analysis & Visualization  
Group wallets based on behavior using KMeans and visualize clusters with PCA.

### 8. Export Final Scores  
Save the wallet IDs and their credit scores to a CSV file.
  
---

## 📈 Flow Architecture

1. **Raw Data (JSON)** → Preprocessing & Feature Engineering  
2. → Exploratory Data Analysis (EDA)  
3. → Model Training for Credit Score Prediction  
4. → Feature Importance Analysis  
5. → Clustering (KMeans + PCA Visualization)  
6. → Final Scoring & Export to CSV  
7. → Analysis (Score Distribution, Wallet Behavior)


---

## 📁 Files

- `credit_score_modeling.ipynb`: The main Jupyter notebook  
- `wallet_credit_scores.csv`: Final output with wallet and assigned credit score  
- `analysis.md`: Detailed wallet behavior analysis  
