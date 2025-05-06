# sp25-b2b-sales-forecasting
Kaggle SP25 Challenge – B2B Sales Forecasting using Time Series ; Ensemble Models

---

## 📊 Feature Importance
The most influential features included:
- `Company_Avg_Sales`
- `InventoryRatio`
- `QuickRatio_InventoryRatio`
- `Sales_Lag1`, `Sales_Lag2`
- `Sentiment_Sensitivity`

---

## 🔁 Model Training Workflow

1. **Data Preprocessing & Feature Engineering**
2. **Train/Validation Split**
3. **Model Building**
    - Train stacked ensemble
    - Evaluate using CV MAE
4. **Hyperparameter Tuning**
    - RandomizedSearchCV
    - Optuna Trials
5. **Final Predictions on Test Set**
6. **Submission File Generation**

---

## 💡 Lessons Learned

This challenge reinforced:
- The power of **feature engineering** over model complexity
- How important it is to ground modeling choices in **business context**
- That combining economic indicators with internal financial metrics can greatly enhance B2B forecasting accuracy

---

## 📎 LinkedIn Post  
📌 [Read about my approach and experience →](#) *(Insert your LinkedIn post link here)*

---

## 📄 License
MIT License. Feel free to use and build upon this project with attribution.

---

## 🤝 Let's Connect

Interested in collaborating on time series or forecasting problems?  
Feel free to reach out or connect with me on www.linkedin.com/in/vaishnavi-karingala-238a82184

