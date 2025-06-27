# Logistic Regression Classifier - Breast Cancer Dataset

## Objective
Build a binary classifier using Logistic Regression to detect breast cancer (malignant vs. benign).

## Steps Performed
- Loaded and cleaned the dataset (dropped `id` and `Unnamed: 32` columns)
- Converted target labels (`M` → 1, `B` → 0)
- Split data into train and test sets
- Standardized features using StandardScaler
- Trained a Logistic Regression model
- Evaluated model using confusion matrix, precision, recall, F1-score, and ROC-AUC
- Visualized the ROC curve
- Tuned classification threshold (tried 0.3 to 0.7) to improve recall or precision
- Explained and plotted the Sigmoid function

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- NumPy

## Key Takeaways
- Logistic Regression uses the sigmoid function to map predictions between 0 and 1, allowing binary classification.
Feature scaling is essential for gradient-based models, such as logistic regression.
- Evaluation metrics, such as precision, recall, F1-score, and ROC-AUC, are crucial for understanding model performance.
- Threshold tuning is important, especially in medical diagnosis scenarios where minimizing false negatives is critical.
- The sigmoid function was visualized to understand its S-shaped curve and how it defines the decision boundary.
- Logistic Regression uses the sigmoid function to convert the linear combination of features into a probability between 0 and 1.

**Formula:**
σ(z) = 1 / (1 + e^(-z))
This allows us to apply a threshold to classify outputs into binary categories.


