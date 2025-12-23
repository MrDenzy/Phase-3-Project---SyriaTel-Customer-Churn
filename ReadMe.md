**SyriaTel Customer Churn Prediction**


**Report Structure**

Phase-3-Project---SyriaTel-Customer-Churn/

|

├── data/

│   └── Telecom.csv

├── notebook/

│   └── index.ipynb

├── output/

│   └── Customer Service Calls vs Churn

│   └── Churn Distribution

│   └── International Plan

│   └── Total Day Minutes

│   └── Top 10 Feature Importances

├── presentation/

│   └── Phase 3 Project Presentation .pdf

│   └── Phase 3 Project Presentation .pptx

├── README.md





**Project Overview**

This project focuses on predicting customer churn for SyriaTel using supervised machine learning classification techniques. Customer churn occurs when customers stop using a company’s services, which can significantly impact revenue. The objective of this project is to build a model that identifies customers who are likely to churn so the business can take proactive retention measures.


**Business Problem**

SyriaTel wants to reduce customer churn by identifying customers who are at risk of leaving. By predicting churn in advance, the company can target these customers with retention strategies such as improved customer support or special offers.


**Data Understanding**

The dataset used in this project comes from the Learn curriculum and contains customer account information, service usage metrics, and churn labels.

1. Target variable: churn (1 = churned, 0 = not churned)

2. Features include: call minutes, charges, international plan usage, and customer service calls


**Methodology**

The project follows a standard machine learning workflow:

1. Data loading and cleaning

2. Exploratory Data Analysis (EDA)

3. Feature selection and train-test split

4. Model training and evaluation

5. Model comparison and interpretation



**Models Used**

1. Logistic Regression: Used as a baseline model due to its simplicity and interpretability.

2. Decision Tree Classifier: Used to capture non-linear relationships and improve churn detection.



**Results**

1. Logistic Regression achieved good overall accuracy but performed poorly in identifying churned customers.

2. The Decision Tree model significantly improved churn recall and achieved a higher ROC-AUC score.

3. Based on performance metrics, the Decision Tree was selected as the better model for this problem.



**Business Recommendation**

1. Customers with frequent customer service calls are more likely to churn.

2. Usage-related features play an important role in churn prediction.

3. Improving customer support and targeting high-risk customers could help reduce churn.



**Conclusion**

This project demonstrates how supervised machine learning classification can be applied to a real-world business problem. The final model provides actionable insights that SyriaTel can use to improve customer retention.