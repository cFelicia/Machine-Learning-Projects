### Heart Disease Prediction using Logistic Regression Model
This project uses a Logistic Regression model to predict the likelihood of heart disease based on patient health attributes. The goal is to build an interpretable baseline model that can classify patients as having heart disease or not, using a well-known clinical dataset.

**Steps Performed:**
1. Data Cleaning – Checked and removed duplicates, verified data balance.
2. Exploratory Data Analysis (EDA) – Visualized distributions and relationships among variables.
3. Feature Scaling – Standardized features.
4. Model Training – Trained a Logistic Regression model to classify heart disease presence.
5. Model Evaluation – Evaluated using Accuracy, Precision, Recall, F1-score, ROC-AUC, and Feature Importance.

**Model Performance**
- Accuracy: 0.80
- AUC: 0.874
- Recall (Heart Disease): 0.85
- The model demonstrates strong predictive performance and effectively balances false positives and false negatives.
  
**Conclusion**
This project demonstrates how Logistic Regression can effectively predict heart disease using clinical data. With an accuracy of 80% and an AUC of 0.87, the model shows strong and balanced predictive performance. Key indicators such as chest pain type, maximum heart rate, and ST-segment slope were identified as the most influential predictors of heart disease. These insights align with known medical evidence and highlight the importance of cardiac stress and exercise metrics in diagnosis.
Future improvements could include testing more complex models like Random Forest or XGBoost, performing hyperparameter tuning, and deploying the model for practical healthcare use.
