1. Data Loading and Exploration:
- The project starts by importing necessary libraries, including Pandas and NumPy, and loading a dataset named 'CreditRisk.csv' using Pandas.
- The shape of the dataset and the count of missing values in each column are checked.

2. Data Preprocessing:
- Missing values in specific columns (Gender, Married, Self_Employed, Dependents, LoanAmount, Loan_Amount_Term, and Credit_History) are filled using different
 strategies (e.g., filling with mean, mode, or specific values)
- Label encoding is applied to convert categorical variables into numerical format using the LabelEncoder from scikit-learn.

3. Data Splitting:
- The dataset is split into training and testing sets using the train_test_split function from scikit-learn.
   
4. Model Training:
- Logistic Regression model is chosen and instantiated (LogisticRegression() from scikit-learn).
- The model is trained using the training data.

5.Model Evaluation:
- Predictions are made on the test set.
- Confusion matrix is calculated using confusion_matrix from scikit-learn.
- Accuracy, recall, precision, and F1-score are calculated using respective functions from scikit-learn.
- Area under the ROC curve (AUROC) is computed using roc_auc_score and plotted using roc_curve.
  
6. Results and Conclusion:
- The project concludes by providing key metrics such as accuracy, recall, precision, F1-score, and AUROC score.
- An AUROC curve is plotted, and the AUROC score is mentioned in the plot.
