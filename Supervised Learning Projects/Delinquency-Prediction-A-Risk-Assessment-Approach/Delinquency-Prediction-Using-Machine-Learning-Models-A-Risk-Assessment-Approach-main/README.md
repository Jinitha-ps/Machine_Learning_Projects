# 💡 Delinquency Prediction Using Machine Learning Models: A Risk Assessment Approach
This project focuses on building and evaluating machine learning models to accurately predict customer delinquency based on historical financial and behavioral data. By proactively identifying customers at risk of failing to make timely payments, financial institutions can optimize their credit risk management strategies and reduce default rates.

🎯 **Project Objective**
The primary goal is to develop a predictive solution that classifies customers as either delinquent (1) or non-delinquent (0). Early identification of at-risk accounts allows businesses to take proactive steps, such as optimizing recovery strategies and improving customer engagement, ultimately providing significant business value by reducing financial risk.



🛠️ **Key Technologies and Models**
Technologies Used
Python: Core programming language.


Pandas & NumPy: Data manipulation and numerical operations.


Scikit-learn (sklearn): Machine learning model implementation and evaluation.


Matplotlib & Seaborn: Exploratory Data Analysis (EDA) and visualization.

Machine Learning Models Evaluated
We compared the performance of three distinct models for this binary classification task:

1)**Random Forest Classifier** 


2)**Logistic Regression**


3)**Multilayer Perceptron (MLP) / Neural Network** 



📊 **Dataset and Key Features**
The project utilized the Delinquency_prediction_dataset.xlsx dataset, which contains 500 entries across 19 columns.



Selected Features for Modeling
The final predictive models were trained using a select set of features, chosen based on data completeness and potential impact:

Missed_Payments

Credit_Utilization

Income

Account_Tenure


Debt_to_Income_Ratio 

Data Insights from EDA
Exploratory Data Analysis (EDA) revealed several key patterns and observations:


Account Tenure: Customers in the '0-1 yr' and '1-2 yr' tenure groups showed the highest number of delinquent accounts.

📈 **Model Performance Summary**
The models were evaluated using standard classification metrics on a test set:

Model	                    Accuracy	   Precision	Recall	F1 Score	AUC-ROC

Random Forest	              0.85	       0.00    	0.00    	0.00	    0.46 

Logistic Regression       	0.86	       0.00	    0.00	    0.00		  0.54 

Neural Network (MLP)      	0.86	       0.00	    0.00	    0.00	    0.46




Credit Score: The box plot comparing credit scores showed that, on average, non-delinquent accounts have a slightly higher median credit score than delinquent accounts, with the delinquent group showing a wider spread in scores.

Note on Metrics: The low scores for Precision, Recall, and F1-Score for the positive class (delinquent) suggest a significant challenge with class imbalance in the dataset, leading most models to default to predicting the majority class (non-delinquent)161616161616161616. The AUC-ROC score is generally a more robust measure in such imbalanced scenarios.

**Feature Importance** (Random Forest)
The most important features in predicting delinquency, according to the Random Forest model, were:
1)Debt_to_Income_Ratio
2)Credit_Utilization
3)Income 

17📝 **Conclusion**

While all models achieved high overall accuracy (due to class imbalance), the Logistic Regression model performed slightly better on the AUC-ROC Score ($\approx 0.54$), indicating a marginally superior ability to distinguish between positive and negative classes compared to the other models18181818. Future work will focus on addressing the class imbalance issue (e.g., through techniques like SMOTE or varying class weights) to improve the models' recall and precision for the delinquent class.



Correlation: The correlation heatmap indicated that the target variable, Delinquent_Account, has a positive correlation with Loan_Balance and Missed_Payments.
