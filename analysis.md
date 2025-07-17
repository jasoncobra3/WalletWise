# 📊 Credit Score Distribution and Wallet Behavior Analysis

## 🎯 Score Distribution (Group Ranges)

The final credit scores (0–500 range) were grouped and analyzed:

| Score Range | Number of Wallets |
|-------------|-------------------|
| 0–100       | 0                 |
| 100–200     | 0                 |
| 200–300     | 0                 |
| 300–400     | ~3                |
| 400–500     | 25                |
| 500–600     | ~32               |
| 600–700     | ~200                |
| 700–800     | ~300                 |
| 800–900     | ~250                |
| 900–1000    | <2500                |


![Score Distribution](score_distribution.png)

---

## 📊 Credit Score Distribution Analysis

### 🔴 Low Credit Scores (0–300)
- **Total Wallets:** 0  
- **Interpretation:** No users fall in the poor credit range, which may indicate good financial behavior across users or prior data filtering.

### 🟠 Below Average Scores (300–500)
- **Wallets:** ~28  
- **Interpretation:** Very few users are at risk or show poor credit health.

### 🟡 Average to Good Scores (500–700)
- **Wallets:** ~232  
- **Insight:** A moderate number of users have acceptable credit, possibly in the process of building or recovering their financial credibility.

### 🟢 Good to Very Good Scores (700–900)
- **Wallets:** ~300  
- **Interpretation:** A strong cluster of users falls within this range, suggesting overall healthy credit behavior.

### 🔵 Excellent Scores (900–1000)
- **Wallets:** <2500  
- **Insight:**  
  - Most wallets belong to users with **high credit scores**.  
  - This may indicate:
    - A strong, financially responsible user base, or  
    - A **bias in the dataset**, where low-score users are underrepresented.

---

## 🔍 Feature Influence (Top Drivers of Score)

The most important features influencing the credit score (as per feature importance analysis) are:

- **Repay-Borrow Ratio**: Indicates how much of the borrowed amount is being repaid — a direct signal of creditworthiness.
- **Liquidation Count**: Frequent liquidations may signal poor financial health or risky behavior.
- **Total Borrow Amount**: Higher borrow amounts can be either good or bad depending on repayment behavior.
- **Borrow Count**: A high number of borrow events shows borrowing frequency.
- **Repay Count**: How consistently the user is repaying.
- **Total Repay Amount**: Total money repaid over time, showcasing repayment strength.

These features are strong indicators of financial discipline and are directly tied to how users manage their credit.

---

## ✅ Final Summary

The dataset is **heavily skewed** toward high credit scores (**900–1000**).

### 📌 Implications:
- The product or platform may be **targeted at financially responsible users**.
- There may be a **data imbalance**, which can:
  - Affect the performance and generalization of a predictive model.
  - Lead to overfitting or biased predictions toward higher scores.


