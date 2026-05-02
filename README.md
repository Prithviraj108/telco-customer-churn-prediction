# telco-customer-churn-prediction
A beginner-friendly ML project to predict customer churn using Logistic Regression and Random Forest. Includes EDA, data cleaning, feature engineering, and model evaluation.

📉 Telco Customer Churn Prediction

A beginner-friendly machine learning project that predicts whether a telecom customer will churn (leave the service), using real-world data. Built with Python on Google Colab.

🧠 Problem Statement

Customer churn is a major challenge for telecom companies. Losing a customer costs far more than retaining one. This project builds a classification model to predict which customers are at risk of churning, so the business can take proactive steps to retain them.

📁 Dataset

- Source: Telco Customer Churn – Kaggle
- Size: ~7,000 customers
- Target Column: Churn Label (Yes / No)
- Features include: Contract type, Monthly Charges, Tenure, Internet Type, Offer, and more.


🔧 Tech Stack

- Tool            ->                Purpose

- Python          ->           Core programming language            
- Pandas          ->           Data manipulation
- NumPy           ->           Numerical operations
- Matplotlib & Seaborn   ->    Data visualisation
- Scikit-learn    ->           ML models and evaluation
- Google Colab    ->           Cloud-based notebook environment
- KaggleHub       ->           Dataset download

📊 Project Workflow

1. Import Libraries
2. Load Data
3. Data Exploration (EDA)
4. Data Cleaning
5. Feature Engineering
6. Train-Test Split
7. Model Training (Logistic Regression)
8. Model Evaluation
9. Improved Model (Random Forest)
10. Feature Importance

🤖 Models Used

Logistic Regression

- Baseline binary classification model
- Simple, interpretable, great starting point

Random Forest

- Ensemble of decision trees
- Higher accuracy, captures complex patterns
- Provides feature importance scores


📈 Results

Model                        Accuracy
Logistic Regression           ~80%
Random Forest                ~82–85%

Note: Accuracy alone can be misleading on imbalanced datasets. F1 Score and Recall were also evaluated via the classification report.


📌 Key Insights from EDA

- Customers on Month-to-Month contracts churn significantly more than yearly subscribers
- Customers with higher monthly charges are more likely to churn
- Tenure (how long a customer has been with the company) is one of the strongest predictors — newer customers churn more


🗂️ Project Structure

telco-customer-churn-prediction/

│

├── telco_churn_clean.py     # Full cleaned Python script

├── README.md                # Project documentation

🚀 How to Run

- Open Google Colab
- Upload telco_churn_clean.py or paste it into a new notebook
- Run all cells top to bottom
- The dataset is downloaded automatically via kagglehub


Make sure you have a Kaggle account and your API key configured for kagglehub to work.


🎓 What I Learned

- Full ML pipeline from raw data to model evaluation
- Handling missing values, encoding categorical variables
- Difference between Logistic Regression and Random Forest
- Evaluating models using Confusion Matrix, Precision, Recall, and F1 Score
- Importance of EDA before modelling


🙋 About

This project was built as part of my journey into Data Science and Machine Learning. It was developed on Google Colab as a hands-on learning exercise and interview preparation project.

📄 License

This project is open source and available under the MIT License.
