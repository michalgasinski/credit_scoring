# Credit Scoring Project

This project involves building a credit scoring model to evaluate the likelihood of a client meeting credit requirements based on demographic and financial data. The project includes data preprocessing, exploratory data analysis, model training, and evaluation.

## Project Overview

- **Data**: The dataset includes training (`data_DS_HW_train.csv`) and test (`data_DS_HW_test.csv`) data, containing demographic, economic, and credit history information for various clients.
  
- **Data Processing and Cleaning**: 
  - **Missing Data**: Missing values were analyzed and imputed differently based on the data type and distribution, using median imputation, zero-filling, or KNN imputation.
  - **Outlier Detection**: Outliers were detected using the Z-score method, with handling methods applied accordingly.
  - **Feature Engineering**: Categorical features were one-hot encoded, and unnecessary columns were removed.

- **Model Training**: A `RandomForestClassifier` was trained, with hyperparameter tuning performed using GridSearchCV. Evaluation metrics include AUC, precision, recall, and ROC and PR curves.

- **Prediction**: The model was used to predict probabilities for test data, and results were saved in `results/data_DS_HW_test_with_probabilities.csv`.
