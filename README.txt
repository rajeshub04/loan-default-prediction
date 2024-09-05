Description---
Developed a machine learning models for a classification problem to predict whether the loan status of a loan applicant will be completed or not.

Motivation--
Importance of loan default prediction in ensuring responsible lending practices.
Safeguarding financial institutions against potential defaults.
Significance in the Indian context, especially with initiatives like Jan Dhan Yojana promoting financial inclusion.

Dataset--
Source: Kaggle Loan Dataset
Size: 81 columns with approximately 113,000 data points
Important features: Borrower APR, Borrower Rate, Prosper Rating, Employment Status, Occupation, Prosper Score, etc.

Outline of the Project--
Exploratory Data Analysis (EDA)
Data Preprocessing
Principal Component Analysis (PCA)
Model Building and Evaluation:
Gaussian Naive Bayes
Logistic Regression
Support Vector Machine (SVM)
Ensemble Methods

Preprocessing Techniques--
Null values were handled by removing columns with >50% nulls and replacing others using mean (for numeric) or mode (for categorical) values.

Model Performance--
Metrics Used: F1 Score for performance evaluation.
Best Model: Logistic Regression achieved 0.84 f1 score ans essembled methods of 0.94 score

Conclusion--
The Ensemble methods (Random Forest and Gradient Boosting) performed the best with an F1 score of 0.94, outperforming Logistic Regression and SVM models.

How to run--
TO RUN THE CODE:FIRST RUN eda.ipynb
THEN RUN SUBSEQUENT MODELS


