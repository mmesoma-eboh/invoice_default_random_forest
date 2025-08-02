# 🔍 Predicting Invoice Payment Defaults with Machine Learning (Random Forest)

This project applies machine learning to simulate and predict payment defaults in invoice trading — a real-world challenge in the growing alternative finance space.

## 🧠 Why This Matters

Invoice trading allows businesses to sell unpaid invoices to investors. But default risk is real — and expensive. This project simulates invoice-level data and uses a **Random Forest Classifier** to predict defaults based on key financial and behavioral features.

## 🚀 Project Highlights

- ✅ Simulated realistic invoice data
- ✅ Used **Random Forest Classifier** for prediction
- ✅ Evaluated performance with precision, recall, and confusion matrix
- ✅ Tackled an alternative finance use case: **risk management in invoice trading**

## 🔍 Key Features

- `client_credit_score`
- `invoice_amount`
- `prior_default_rate`
- `client_industry`
- `invoice_term`

## 📊 Results

- **Overall Accuracy**: 74%
- **Strength**: High recall for non-defaulters
- **Challenge**: Low recall for defaulters due to class imbalance

## ⚙️ Tech Stack

- Python
- Pandas / NumPy
- Scikit-learn (Random Forest Classifier, EDA, evaluation)
- Seaborn / Matplotlib for visuals

## 📈 Future Enhancements

- Address class imbalance with SMOTE or class weights
- Test advanced models (e.g., XGBoost, LightGBM)
- Add real-world features (e.g., repayment behavior, invoice metadata)
- Deploy as a scoring API or dashboard

## 📁 Project Structure

