# 🧠 Credit Score Modeling and Wallet Segmentation

This project involves clustering customer wallets based on behavioral and financial features, and assigning them a credit score using machine learning models.

## 🔧 Methodology

1. **Data Preprocessing**  
   - Numeric-only features selected  
   - Missing values handled  
   - Standardization with `StandardScaler`

2. **Clustering**  
   - Used KMeans to cluster wallets  
   - Optimal `k` determined using Elbow method  
   - Visualized clusters using PCA (2D)

3. **Modeling**  
   - Built regression models to assign a credit score to each wallet  
   - Tried Linear Regression, Random Forest, and XGBoost  
   - Selected model based on R² and RMSE scores

4. **Feature Importance**  
   - Evaluated feature importance from the best model  
   - Used it to understand key drivers of the credit score

## 📈 Flow Architecture

1. Data → Preprocessing  
2. → Clustering (KMeans)  
3. → Score prediction (Model training)  
4. → Final scoring + Export CSV  
5. → Analysis (Score distribution, wallet behavior)

---

## 📁 Files

- `credit_score_modeling.ipynb`: The main Jupyter notebook  
- `wallet_credit_scores.csv`: Final output with wallet and assigned credit score  
- `analysis.md`: Detailed wallet behavior analysis  
