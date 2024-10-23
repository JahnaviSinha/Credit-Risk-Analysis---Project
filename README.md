##Credit Risk Default Prediction using Machine Learning Models: Achieving 97% Accuracy
Credit risk analysis is vital for financial institutions as it helps them gauge the likelihood of borrowers defaulting on loans. In this project, we leveraged the American Express dataset to predict credit risk using logistic regression alongside other machine learning models. Our goal was to pinpoint the most effective model for predicting credit card defaults and identify the key variables influencing credit risk.
Our results indicate that XGBoost was the top-performing model, delivering an impressive accuracy of 97%, a precision of 91%, an F1-score of 91%, and an AUC value of 92%. While logistic regression and other models also yielded solid performance, XGBoost stood out. Notably, the most influential factors in predicting credit card defaults were the credit score, credit limit utilization, and employment duration. Interestingly, the borrower's age proved insignificant in predicting defaults, underscoring the importance of focusing on other variables in credit risk assessments.
These findings offer valuable insights for financial institutions, suggesting that advanced machine learning techniques like XGBoost can enhance their ability to assess and manage credit risk, ultimately minimizing losses from defaults.

##Dataset Overview
The dataset used in this analysis is from the "AmExpert 2021 CODELAB - Machine Learning Hackathon", hosted by HackerEarth. It contains data from American Express, which provides a range of payment products and services. The original dataset had 45,528 rows and 19 columns, but we narrowed it down to 30,000 rows and 19 columns for our study. The target variable, "credit_card_default," is binary (0 or 1), representing the likelihood of default. The dataset consists of 6 categorical features and 13 numerical features.
You can access the dataset here: AmExpert Codelab 2021 on Kaggle


##Model Performance Comparison
Model	Accuracy
Logistic Regression	0.9464
Random Forest	0.9650
Decision Tree	0.9663
LightGBM	0.9668
KNN	0.9681
CatBoost	0.9683
XGBoost	0.9734

##Future Directions
Future work in this domain could involve comparing the performance of additional models, such as Support Vector Machines, Neural Networks, and Deep Learning, to see how they fare in various scenarios. Additionally, incorporating alternative data sources like social media activity could further refine credit risk predictions.
