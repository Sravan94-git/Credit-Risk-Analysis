# 💳 FinPulse – AI-Powered Credit Risk Analysis Platform

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
[![.NET](https://img.shields.io/badge/.NET-ASP.NET%20Core%208-purple.svg)](https://dotnet.microsoft.com/)
[![React](https://img.shields.io/badge/Frontend-React-61DAFB.svg)](https://react.dev/)
[![Azure](https://img.shields.io/badge/Cloud-Microsoft%20Azure-0078D4.svg)](https://azure.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**FinPulse** is an AI-powered Credit Risk Analysis Platform that combines **Machine Learning**, **Big Data Processing**, **React**, **ASP.NET Core Web API**, and **Microsoft Azure** to deliver intelligent loan default predictions. The platform analyzes large-scale financial datasets, provides secure real-time risk assessments through a modern and intuitive user interface, and leverages cloud-native services for scalable deployment, authentication, and prediction history management.
---

# 📊 Dataset Description

The model was trained on a dataset containing **1,000,000 loan applicant records** with **51 financial and demographic features**.

### Target Variable
- **LoanApproved**
  - `1` → Approved
  - `0` → Not Approved

### Important Features
- Credit Score
- Annual Income
- Loan Amount
- Debt-to-Income Ratio
- Bankruptcy History
- Employment Status
- Loan Term
- Existing Debt
- Number of Credit Lines
- Payment History

The dataset simulates real-world lending scenarios with a mixture of numerical and categorical attributes.

---

# ✨ Key Features

- 🤖 AI-powered loan default prediction using Machine Learning.
- ⚡ Distributed data preprocessing using **Hadoop** and **PySpark**.
- 📉 Reduced **51 features to 14 important features**, improving training efficiency by approximately **30%**.
- 📊 Compared multiple machine learning algorithms using both **PySpark MLlib** and **Scikit-learn**.
- 🎯 Achieved **79.87% Accuracy** using **Random Forest**.
- 🚨 Achieved **97.25% Recall** using **Gradient Boosting** for identifying high-risk borrowers.
- 🌐 Developed a fully functional **React** frontend with a modern, responsive, and intuitive UI/UX.
- 🔗 Built secure RESTful APIs using **ASP.NET Core Web API** following Clean Architecture principles.
- 🔐 Implemented **JWT Authentication** and role-based authorization.
- ☁️ Integrated **Azure Cosmos DB** for scalable storage of users and prediction history.
- 🚀 Deployed the complete application on **Microsoft Azure** using cloud-native services.
- 📈 Stores prediction history, enabling users to review previous loan assessments.

---

# 🧠 Machine Learning Models

The following algorithms were trained and evaluated:

- Logistic Regression
- Random Forest
- Naive Bayes
- Gradient Boosting

Each model was implemented using:

- ✅ Scikit-learn
- ✅ PySpark MLlib

---

# 📈 Performance Summary

| Model | Framework | Performance |
|--------|-----------|------------|
| Random Forest | PySpark | **79.87% Accuracy** |
| Gradient Boosting | Scikit-learn | **97.25% Recall** |
| Logistic Regression | PySpark / Scikit-learn | Baseline Model |
| Naive Bayes | PySpark / Scikit-learn | Comparative Analysis |

---

# 💻 Full-Stack Features

- User Registration & Login
- JWT Authentication
- Loan Prediction Form
- Real-Time Credit Risk Prediction
- Prediction History
- Responsive Dashboard
- Secure REST APIs
- Input Validation
- Exception Handling
- Cloud Deployment on Microsoft Azure

---

# 🛠️ Tech Stack

### Frontend
- React
- React Router
- Axios
- HTML5
- CSS3
- JavaScript

### Backend
- ASP.NET Core Web API
- C#
- REST APIs
- JWT Authentication

### Machine Learning
- Python
- Scikit-learn
- PySpark
- Hadoop
- Pandas
- NumPy

### Database
- Azure Cosmos DB

### Cloud
- Microsoft Azure
- Azure App Service
- Azure Static Web Apps
- Azure Cosmos DB
- Azure Key Vault
- Azure Application Insights

### Tools
- Git
- GitHub
- Postman
- Visual Studio
- VS Code

---

# 🏗️ System Architecture

```text
               React Frontend
                      │
                      ▼
          ASP.NET Core Web API
                      │
     ┌────────────────┼────────────────┐
     ▼                ▼                ▼
 ML Prediction    Cosmos DB      Authentication
     │
     ▼
PySpark / Scikit-learn Models
```

---

# 🚀 Future Enhancements

- Explainable AI using SHAP/LIME
- Power BI Dashboard
- Docker Containerization
- Kubernetes Deployment
- CI/CD using GitHub Actions or Azure DevOps
- Email Notifications
- Loan Recommendation System

---

# 👨‍💻 Author

**Sunkara Sravan Kumar Reddy**

AI Engineer | Full-Stack Developer | Machine Learning Enthusiast
