# 🛡️ Credit Card Fraud Detection - Machine Learning Project

## 📌 Overview
This project applies supervised machine learning techniques to detect fraudulent credit card transactions using real-world financial data. The goal is to accurately identify potentially fraudulent activity while minimizing false positives.

## 📂 Dataset
- Contains anonymized transaction records with features derived from PCA transformation
- Includes `Amount`, `Time`, and a binary `Class` label (0 = legitimate, 1 = fraud)
- Due to data sensitivity, the dataset is not publicly linked

## 📊 Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## 📈 Evaluation Metrics

| Model               | Accuracy | AUC Score |
|--------------------|----------|-----------|
| Logistic Regression | 0.9733   | 0.9700    |
| Decision Tree       | 0.9661   | 0.9459    |
| Random Forest       | 0.9994   | 0.9736    |
| XGBoost             | 0.9990   | 0.9752    |

## 💾 Artifacts
- Jupyter Notebook (`.ipynb`) with full code and analysis
- `creditcard_predictions.csv`: Model predictions
- `.pkl` files: Trained models for deployment (optional)

## 📊 Power BI Ready
The exported predictions CSV can be used to create visual dashboards in Power BI for further business insights.

## 🛠️ Tech Stack
- Python (Pandas, Scikit-learn, XGBoost)
- Google Colab
- Power BI (optional)
- GitHub

## 🚀 How to Use
1. Clone the repository
2. Open the notebook in Google Colab
3. Upload the dataset (privately available)
4. Run all cells to train and evaluate models
5. Export predictions and analyze visualizations

---

📍 **Author**: Rachit Patwa
🔗 **LinkedIn**: www.linkedin.com/in/rachitpatwa1076
