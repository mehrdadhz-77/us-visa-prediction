## 🔍 Overview
This Jupyter Notebook implements a full ML workflow to predict the US visa certification outcomes using U.S. Department of Labor OFLC datasets. It cleans and explores application data, engineers features, trains classification models, and summarizes the findings and most important features for the visa approval. 

## 📝 Work Completed
This project includes:

- 🔄 **Data Preprocessing**: Cleaning, transforming, and imputing missing values  
- 🔎 **Exploratory Data Analysis**: Generating statistical summaries and visualizations to uncover patterns  
- ✨ **Feature Engineering**: Creating and selecting the most informative predictor variables  
- 🤖 **Model Training**: Training and evaluating multiple classification algorithms  
- 🎛️ **Hyperparameter Tuning**: Optimizing model parameters with grid search and cross-validation  
- 🏆 **Best Model Selection**: Identifying XGBoost as the top-performing model based on evaluation metrics  

## 📑 Findings Report
Below is a concise summary of the analysis:

- 🎯 Best Model Performance: The XGBoost model achieved __76% accuracy__ and __82.9% F1-score__ on the test set.

- 📊 Top Influential Features (in order):

  1. Applicant's Job Experience – years of prior experience contributing most to approval probability.

  2. Applicant's Education Level – higher degrees correlate with higher approval rates.

  3. Region of Employment – geographic location impacts certification likelihood (e.g., CA, TX).

## 📂 Use Case
Employers, immigration consultants, and applicants can:
- Estimate certification likelihood before submission.
- Understand the impact of various application factors.
- Optimize application details to improve approval chances.



## 🛠️ Tech Stack
- Python 3.8+ & Jupyter Notebook
- 🔢 pandas, numpy for data processing
- 📊 matplotlib, seaborn for visualizations
- 🤖 scikit-learn, xgboost for modeling
- 🧪 imbalanced-learn for handling skewed classes
