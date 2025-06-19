# Credit Card Behaviour Score Prediction

This project predicts the likelihood of a customer defaulting on their credit card payment in the upcoming month, using behavior-based features and classification techniques.

## Project Highlights

- ✅ **Dataset**: Credit card behavioral data of 30,000+ customers  
- 🧠 **Approach**: Classification models with financial domain feature engineering  
- ⚖️ **Class Imbalance**: Handled using SMOTE and Tomek Links  
- 🧪 **Models Used**: Logistic Regression, LightGBM, XGBoost, CatBoost  
- 🔁 **Ensemble Strategy**: Stacked ensemble with CatBoost as meta-learner  
- 🎯 **Optimized For**: F2 score to minimize false negatives (high-risk defaults)

## Requirements

- Python 3.8+
- scikit-learn
- lightgbm
- xgboost
- catboost
- imbalanced-learn
- pandas, numpy, matplotlib, seaborn

## Run the Project

```bash
# Clone repo and install dependencies
pip install -r requirements.txt

# Run notebook end-to-end
jupyter notebook creditcard_FC.ipynb
```

Thanks :)
