# Credit Risk Analysis using Machine Learning

Credit risk analysis is a crucial process for financial institutions to assess the likelihood of borrowers defaulting on their loans. This project leverages various machine learning algorithms to analyze credit risk, with implementations in both **PySpark** and **scikit-learn**. By comparing the efficiency and performance of these algorithms on a large-scale dataset, this study provides valuable insights for building robust credit scoring systems.

## Dataset Description

The dataset used for this project comprises **1,000,000 entries** and **51 features**. It captures both financial and demographic information of loan applicants.

* **Target Variable**: `LoanApproved` (1 for approved, 0 for not approved)
* **Key Features**:
    * `CreditScore`
    * `AnnualIncome`
    * `LoanAmount`
    * `DebtToIncomeRatio`
    * `BankruptcyHistory`
    * ...and more

The data simulates real-world conditions with daily variability. Categorical variables were appropriately encoded, and special attention was paid to the class distribution of the `LoanApproved` target.

## Machine Learning Models Used

The following machine learning models were trained and evaluated:

* Logistic Regression
* Random Forest
* Naive Bayes
* Gradient Boosting

Each model was implemented using two different frameworks to compare their performance and scalability:

* ✅ scikit-learn
* ✅ PySpark MLlib

## Key Insights

* **PySpark Random Forest** achieved the **highest overall performance** in terms of F1-Score, making it the superior choice for handling large-scale parallel processing.
* **scikit-learn Gradient Boosting** excelled in **Recall**, demonstrating its effectiveness when the cost of missing a defaulter is significantly higher than a false positive.

These findings highlight the trade-offs between different models and frameworks, helping financial institutions to choose the most suitable algorithm for their specific risk mitigation goals.

    * Run the cells sequentially to perform data preprocessing, model training, and evaluation.

**Note**: If you do not have Jupyter installed, you can install it via pip:
`pip install notebook`
