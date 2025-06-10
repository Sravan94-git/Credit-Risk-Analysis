🏦 Credit Risk Analysis using Machine Learning

Credit risk analysis is critical in determining the chance of borrowers defaulting on their loans. It enables financial institutions to make informed lending decisions and mitigate potential losses. This project focuses on analyzing credit risk using various machine learning algorithms implemented in both PySpark and scikit-learn. Through preprocessing, model training, and performance evaluation, this study compares algorithm efficiency in handling large-scale financial data.

📁 Dataset Description
The dataset contains 1,000,000 entries and 51 features, capturing both financial and demographic aspects of loan applicants. The target variable is LoanApproved, indicating whether the loan was approved (1) or not (0).

🔑 Key Features
CreditScore

AnnualIncome

LoanAmount

DebtToIncomeRatio

BankruptcyHistory

...and others

Each row simulates real-world data with daily variability to reflect practical financial modeling conditions. Categorical variables were encoded appropriately, and special attention was given to the LoanApproved class distribution.

🔍 Machine Learning Models Used

We trained and evaluated the following models:

Logistic Regression

Random Forest

Naive Bayes

Gradient Boosting

Each of these models was implemented using:

✅ scikit-learn

✅ PySpark MLlib

🔍 Key Insights
PySpark Random Forest achieved the highest overall performance in terms of F1-Score, making it the best choice for large-scale parallel processing.

scikit-learn Gradient Boosting excelled in Recall, making it ideal when missing a defaulter is costlier than a false positive.

These insights help institutions build more robust and scalable credit scoring systems.

🚀 How to Run
1. Clone the Repository
git clone https://github.com/yourusername/credit-risk-analysis.git
cd credit-risk-analysis
2. Launch Jupyter Notebook
jupyter notebook
3. Run the Notebook
Open the credit_risk_analysis.ipynb or relevant notebook file from the browser interface that appears.

Run the cells sequentially to preprocess the data, train models, and view evaluation results.

Note: Ensure you have Jupyter installed (pip install notebook) if it's not included in your environment.
