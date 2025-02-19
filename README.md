# Responsible_AI
Course work for  Responsible AI [AI&amp;DS-302]

### Assignment 1: Proxy Features

"Proxy features" in AI ethics are known as the hidden biases in data which the model learns and uses in the predictions or outcomes. Even if an AI model does not explicitly incorporate protected characteristics such as race, gender, or income, it can make use of other data points-colour discrimination, which would indirectly represent these characteristics-such as ZIP codes, job titles, or buying behaviour.

This project analyzes loan approval data, aiming to understand feature importance and mitigate potential biases.  It begins by preprocessing the data, including handling missing values and converting categorical features to numerical ones.  Variance Inflation Factor (VIF) is used to detect and address multicollinearity, identifying proxy variables that might introduce bias. Feature importance is then assessed using a Decision Tree Regressor and R-squared values, revealing the predictive power of each feature. The analysis identifies "Credit_History" as the most influential factor, while others may be proxy variables requiring further investigation to ensure fairness and transparency. 

### Assignment 2: Impact of Differential Privacy on Decision Tree Regression Performance

This project evaluates the impact of Differential Privacy (DP) on data utility and model performance using a Decision Tree Regressor. We trained four models: one on original data, one on DP-processed data, one with DP-enhanced training on original data, and one with DP-enhanced training on DP data. Key metrics such as R² score, MAE, RMSE, and MAPE were analyzed to compare performance. The results indicate that while DP reduces data utility, DP-enhanced training helps mitigate performance loss. This study highlights the trade-off between privacy and predictive accuracy in machine learning.
