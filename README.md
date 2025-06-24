
# 🏡 -Real-Estate-Price-Predictor Model

🚀 An end-to-end Machine Learning project for predicting house prices using cutting-edge regression techniques, inspired by [Kaggle’s House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

## 📌 Project Overview
This project involves building a robust predictive model using structured housing data with over 80 features. The focus is on preprocessing, feature engineering, and testing multiple ML models to find the best performer.

**Dataset Size:**
- 🏠 Training: 1,460 entries
- 🏠 Test: 1,459 entries

---

## 🔧 Workflow Summary

- ✅ **Data Cleaning**: Handled missing values and outliers
- ✅ **Feature Engineering**: Created and transformed features
- ✅ **Encoding**: One-hot encoded categorical variables
- ✅ **Scaling**: Standardized numerical data
- ✅ **Modeling**: Trained multiple regressors
- ✅ **Cross-Validation**: Used K-Fold CV to avoid overfitting
- ✅ **Hyperparameter Tuning**: Applied GridSearchCV for optimization

---

## 🤖 Model Performance

| Model                   | R² Score | Best Hyperparameters |
|------------------------|----------|-----------------------|
| Gradient Boosting 🏆   | **0.8901** | `learning_rate=0.1, max_depth=3, n_estimators=200` |
| XGBoost                | 0.8807   | `learning_rate=0.05, max_depth=3, n_estimators=200` |
| Random Forest          | 0.8585   | `max_depth=20, min_samples_split=2, n_estimators=100` |

---

## 💡 Key Takeaways

- 🎯 Gradient Boosting had the best performance due to its ensemble learning power.
- ⚙️ Feature engineering and tuning drastically improved accuracy.
- 🔄 Cross-validation ensured generalization and avoided overfitting.

---

## 🚀 Next Steps

- Deploying the model as a web application using **Flask** or **Streamlit**.

---

## 📁 Project Structure

├── data/ # Dataset folder
├── notebooks/ # Jupyter notebooks (EDA, Modeling)
├── models/ # Saved trained models
├── main.py # Script for model training
├── requirements.txt # Python dependencies
└── README.md # This file

🔗 Resources
📊 Kaggle Competition: House Prices: Advanced Regression Techniques

🙌 Acknowledgements
This project is for learning and demonstration purposes in the field of Machine Learning and Data Science.

📬 Connect with Me
GitHub: @namannayan

LinkedIn: https://www.linkedin.com/in/namannayan/





