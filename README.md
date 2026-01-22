# Customer-churn-analysis-in-e-Commerce
End-to-end e-commerce customer churn analysis using machine learning, survival analysis, and customer segmentation to reduce revenue loss and improve retention strategies
Customer churn in e-commerce is significantly higher than in traditional businesses, reaching rates of up to 80% (Wu & Meng, 2016). In this dataset, the observed churn rate is 17%, representing a substantial revenue risk if not proactively managed.

This project focuses on predicting customer churn, quantifying revenue loss, and delivering actionable business recommendations through machine learning, survival analysis, customer segmentation, and an interactive dashboard.

🎯 Business Objectives

Predict customers who are likely to churn

Identify key drivers behind churn behavior

Estimate loss opportunity and potential revenue uplift

Build customer personas for targeted retention strategies

Enable real-time business monitoring via an interactive dashboard

🏆 Key Results & Business Impact

Tenure and Customer Complaints are the strongest predictors of churn

Customers with no complaints, married status, credit card payments, and grocery purchases have the highest survival probability

Estimated loss opportunity avoided: 💰 $910,687

Estimated revenue uplift: 💹 $150,000+

Revenue Uplift Breakdown
Category	Estimated Uplift
Grocery Orders	$42,448
Credit Card Payments	$91,785
Debit Card Payments	$78,543
🧠 Analytical Approach
1️⃣ Exploratory Data Analysis (EDA)

Dataset contains 5,630 observations and 20 variables

15 numerical features

5 categorical features

2 target variables

Strong correlations observed between churn and:

Tenure

Complaints

Cashback Amount

Preferred Order Category

2️⃣ Supervised Machine Learning

Built multiple classification models with:

Feature engineering

Class imbalance handling

Hyperparameter tuning

Key churn drivers:

Tenure

Complaint

Number of Addresses

Cashback Amount

3️⃣ Survival Analysis

Applied:

Kaplan-Meier Survival Curves

Cox Proportional Hazard (CPH) Model

Predicted future churn probability over time

Identified customer groups with the highest retention likelihood

4️⃣ Customer Segmentation (Unsupervised Learning)

Techniques used:

RFM Segmentation

K-Means

Gaussian Mixture Models

Priority retention segments:

Loyal Customers

New Customers

Promising Customers

Lost Potential Customers

5️⃣ Business Simulation & Dashboard

Simulated:

Churn-driven revenue loss

Retention-based revenue uplift

Built an interactive Power BI dashboard to monitor:

Business metrics

Operational KPIs

Sales performance

🛠 Tools & Technologies

Programming: Python

IDE: JupyterLab

Version Control: Git & GitHub

Visualization: Power BI

📚 Python Libraries

Pandas, NumPy

Scikit-learn

Imbalanced-learn

Feature-engine

Lifelines (Kaplan-Meier, CoxPH)

K-Means, Gaussian Mixture Models

📊 Dataset

E-Commerce Customer Churn Analysis and Prediction
Source: Kaggle
🔗 https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction

📁 Repository Structure

EDA_Churn_Analysis_Ecommerce_Customer_.ipynb
→ Business understanding, EDA, bivariate & multivariate insights

Supervised_Classification_Churn_Analysis_Ecommerce_Customer.ipynb
→ Preprocessing, modeling, imbalance handling, SHAP feature importance

Model_Survival_Analysis_Churn_Analysis_Ecommerce_Customer.ipynb
→ Kaplan-Meier, CoxPH, churn prediction, revenue impact analysis

Unsupervised_Churn_Analysis_Ecommerce_Customer.ipynb
→ RFM segmentation, clustering, customer strategy development

ANN_E-Commerce.pbix
→ Interactive Power BI dashboard

Churn Analysis Ecommerce Customer-Presentasi-ANNTeam_TSDN-2022.pdf
→ Project presentation summary
