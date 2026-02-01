🏥 ***Hospital Readmission Risk Predictor***

Built and deployed a Random Forest–based machine learning system to predict high-risk hospital readmissions, covering data preprocessing, EDA, model evaluation, and Streamlit deployment.

🔍 **Problem Statement**

Hospital readmissions increase operational costs and signal gaps in patient care.
This project predicts readmission risk at admission time, enabling early clinical intervention and better resource planning.

🧠 **Solution Overview**

> Engineered a rule-based target variable using healthcare domain logic

> Built a full ML pipeline from raw data to deployed application

> Compared baseline and ensemble models

> Deployed the final model as an interactive web app

📊 **Dataset & Feature Engineering**

> Uses a simulated healthcare dataset

> Engineered a binary High-Risk Readmission label based on:

    Age > 65

    Chronic conditions (Cancer, Diabetes, Heart Disease)

    Emergency/Elective admission

    Abnormal/Inconclusive test results 

⚙️ **Machine Learning Pipeline**

- Data Processing

- Removed duplicates and irrelevant columns

- Handled missing values

- Encoded categorical features

- Applied feature scaling

- Exploratory Data Analysis

- Class imbalance detection

- Feature distribution and correlation analysis

- Risk-factor visualization using Seaborn & Matplotlib 

🤖 **Models & Evaluation**

_Model	Purpose	Outcome_

| Model | | Type | | Performance |
| :---: | | :---: | | :---: |
| Logistic Regression |	| Baseline |	| Moderate performance |
| Random Forest	| | Final model |	| Higher accuracy & F1-score |


➡️ _Random Forest selected for deployment due to robustness and generalization performance._

🌐 **Deployment**

> Developed a Streamlit web application

> Real-time prediction based on patient inputs

> Model serialized using pickle for production use 

🛠️ **Tech Stack**

> Languages: _Python_

> ML: _Scikit-learn, Random Forest, Logistic Regression_

> Data: _Pandas, NumPy_

> Visualization: _Matplotlib, Seaborn_

> Deployment: _Streamlit_

> Model Persistence: _Pickle_

📌 **Key Highlights**

> Designed a complete end-to-end ML pipeline

> Applied domain-driven feature engineering

> Performed model comparison and selection

> Deployed a production-ready ML model

> Demonstrated real-world healthcare problem solving

📂 **Repository Structure**
├── data/
├── notebooks/
├── model/
├── app.py
├── requirements.txt
└── README.md

🔮 **Future Improvements**

> Deployment on a reliable destination (Vercel / AWS / Azure)

> Train on real hospital outcome data

> Add explainability (SHAP/LIME)

> Feature expansion (comorbidities, patient history)
