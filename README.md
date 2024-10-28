# Credit Scoring Analysis Project 💳

This project focuses on creating an advanced **credit scoring model** to assess a client’s likelihood of meeting credit requirements based on demographic and financial data. Designed for real-world finance applications, the model demonstrates data-driven approaches to improving risk assessment for more informed credit decisions. Using Python, this analysis includes structured data preprocessing, feature engineering, model development, and evaluation, showcasing the power of data science in finance.

## 🔍 Project Objectives

1. **Data Cleaning & Transformation**: Process and clean raw client data, addressing missing values, outliers, and data inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Visualize and interpret patterns in client demographics, economic data, and credit histories to uncover indicators of creditworthiness.
3. **Model Development**: Train a predictive model for credit scoring using optimized parameters.
4. **Evaluation & Insights**: Assess the model’s performance using industry-relevant metrics and generate insights into the predictors of creditworthiness.

This project serves as both a practical demonstration of data science skills and a showcase of industry-relevant insights for recruiters and professionals.

## 📊 Data Analysis Workflow

The project applies a structured, data-driven approach to generate actionable insights. Here’s an overview of the methodology:

### 1. Data Preparation 🧹

   - **Data Cleaning**: Missing values were treated using median imputation, zero-filling, or KNN imputation depending on the feature type and distribution.
   - **Outlier Detection**: Outliers were detected with the Z-score method and addressed through transformations or removals.
   - **Feature Engineering**: Created new features from raw data, one-hot encoded categorical variables, and removed irrelevant columns to enhance model accuracy.
   
### 2. Exploratory Data Analysis 📈

   - **Client Demographics**: Analyzed patterns across age, income, employment status, and other demographic variables to observe how they correlate with credit outcomes.
   - **Financial Behavior**: Assessed economic variables, such as income stability and spending patterns, to understand financial health.
   - **Credit Histories**: Examined credit history, including past loans and repayments, to evaluate historical creditworthiness.

### 3. Model Training 🔧

   - **Model Selection**: Chose `RandomForestClassifier` for its robustness in handling imbalanced classes and its interpretability in financial risk modeling.
   - **Hyperparameter Tuning**: Used `GridSearchCV` to optimize model parameters, balancing performance and generalizability.
   - **Performance Metrics**: Assessed with AUC, precision, recall, and ROC and PR curves for a comprehensive evaluation.

### 4. Model Evaluation & Prediction 🧠

   - **Evaluation**: Analyzed performance metrics on test data to validate the model’s predictive accuracy and reliability.
   - **Prediction**: Generated probability scores for each client, saving predictions to `results/data_DS_HW_test_with_probabilities.csv`.

## 🏆 Key Results

1. **Top Predictors**: Features related to income stability, previous credit history, and employment status emerged as top predictors of creditworthiness.
2. **Model Accuracy**: Achieved high AUC and precision, with reliable recall, indicating the model’s robustness in real-world application.
3. **Insightful Trends**: Observed trends in client demographics and financial stability, suggesting key focus areas for credit risk mitigation.

## 📌 Summary & Takeaways

This project demonstrates a complete credit scoring model, providing recruiters with a practical example of data science skills applied to finance. Insights from the model can guide lending decisions, highlighting predictors of default risk and helping to identify high-risk profiles.

## 🌟 Future Directions

- **Model Expansion**: Incorporate additional financial history features to enhance model accuracy.
- **Real-Time Scoring**: Develop a pipeline for real-time scoring, making the model suitable for operational environments.
- **Advanced Feature Engineering**: Implement advanced features like credit utilization rates and account age for more nuanced predictions.
