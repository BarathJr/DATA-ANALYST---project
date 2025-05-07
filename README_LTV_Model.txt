
# Customer Lifetime Value (LTV) Prediction Model

## 📌 Objective
Predict the lifetime value (LTV) of customers based on historical purchase behavior to aid targeted marketing strategies.

## 🛠️ Tools Used
- Python
- XGBoost
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 📈 Features Engineered
- **Recency**: Days since the last transaction
- **Frequency**: Number of transactions
- **AOV**: Average Order Value (Total Spend / Frequency)
- **Total Spend**: Sum of all transactions
- **Customer Age**: Days since first transaction

## 📦 Model
- **Model Used**: XGBoost Regressor
- **Evaluation Metrics**:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)

## 🎯 Output
- Predicted LTV for each customer
- Segmentation into: Low, Medium, High, Top
- Visualizations: LTV distribution
- Output CSV: `customer_ltv_predictions.csv`

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn
   ```
2. Run the notebook or script.
3. Check the console for MAE/RMSE and review the generated `customer_ltv_predictions.csv`.

## 📁 Files Generated
- `customer_ltv_predictions.csv`: Final LTV and segmentation for each customer

---
