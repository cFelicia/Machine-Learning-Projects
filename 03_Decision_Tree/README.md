### Iris Flower Classification using Decision Tree Classifier
This project applies a Decision Tree Classifier to predict Iris flower species based on petal and sepal measurements. The goal is to demonstrate how tree-based models can classify data by learning simple, interpretable decision rules.

**Workflow**
- Import libraries pandas, scikit-learn, and matplotlib.
- Load dataset using load_iris() from scikit-learn.
- Split data into training and testing sets.
- Train model using DecisionTreeClassifier()
- Make predictions on the test set
- Evaluate performance using Accuracy Score, Classification Report, and Confusion Matrix

**Model Performance**
- Accuracy: 1.0 (100%)
- Classification Report: Precision, recall, and F1-scores are all 1.00, showing no false predictions.
- The model achieved perfect classification, accurately predicting all test samples.

**Conclusion**
The Decision Tree Classifier effectively captures the relationships between flower features and species and accurately predicts Iris species with 100% accuracy. This demonstrates how tree-based algorithms can generate interpretable decision boundaries for classification tasks on structured datasets.
