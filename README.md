# 📊 Customer Churn Prediction  

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Churn%20Prediction-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Model-Logistic%20Regression%20%26%20Random%20Forest-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Accuracy-79%25-orange?style=for-the-badge" />
</p>  

## 🚀 Project Overview  
Customer churn is a major challenge for businesses. This project builds **Machine Learning models** to predict whether a customer will churn (leave) or stay, based on customer behavior and service usage data.  

We implemented and compared two ML models:  
- ✅ **Logistic Regression**  
- 🌲 **Random Forest Classifier**  

---

## 📂 Dataset  
- **Source**: `churn.csv`  
- **Target Variable**: `Churn` (0 = No, 1 = Yes)  
- **Features**: Customer demographics, account details, service usage, etc.  

---

## 🛠️ Steps Followed  

1. **Data Cleaning** 🧹  
   - Handled missing values  
   - Removed duplicates  
   - Converted categorical variables into numerical format  

2. **Exploratory Data Analysis (EDA)** 🔍  
   - Visualized churn distribution  
   - Checked correlations  
   - Plotted categorical vs. churn  

3. **Feature Engineering** 🛠️  
   - Label Encoding & One-Hot Encoding  
   - Scaling numerical features  

4. **Model Building** 🤖  
   - Logistic Regression  
   - Random Forest  

5. **Model Evaluation** 📏  
   - Accuracy  
   - Confusion Matrix  
   - ROC-AUC Score  
   - Classification Report  

---

## 📊 Results  

### Logistic Regression  
- **Accuracy**: `79.13%`  
- **ROC AUC**: `0.84`  
- **Confusion Matrix**:  
[[922 113]
[181 193]]

- **Observation**: Good precision for churn prediction but recall could improve.  

---

### Random Forest  
- **Accuracy**: `79.35%`  
- **ROC AUC**: `0.83`  
- **Confusion Matrix**:  

[[936 99]
[192 182]]

- **Observation**: Higher recall compared to Logistic Regression, slightly better at identifying non-churners.  

---

## 📈 Model Comparison  

| Model               | Accuracy | ROC AUC | Strengths |
|----------------------|----------|---------|-----------|
| Logistic Regression  | 79.1%    | 0.84    | Simple, interpretable |
| Random Forest        | 79.3%    | 0.83    | Captures non-linear relationships |

👉 Both models performed similarly. Logistic Regression has slightly better ROC-AUC, while Random Forest captures complex patterns.  

---

## ⚡ Future Improvements  
- Use **SMOTE** or class weighting to handle imbalance  
- Try **XGBoost / LightGBM** for boosting performance  
- Hyperparameter tuning with **GridSearchCV**  
- Deploy the model as a **Flask/Django Web App**  

---

## 📌 Tech Stack  
- Python 🐍  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 🎯 Conclusion  
This project demonstrates how **Machine Learning can predict customer churn** with ~79% accuracy.  
Businesses can use this model to identify at-risk customers and take proactive steps to improve retention.  

---

## 💡 How to Run the Project  

```bash
```
# Clone the repo
git clone https://github.com/yourusername/churn-prediction.git

# Navigate to project folder
cd churn-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook churn_prediction.ipynb


# 🏆 Author

👩‍💻 Kareem Basha Shaik

🌐 LinkedIn

🐙 GitHub

✨ Passionate about Data Science & Machine Learning
