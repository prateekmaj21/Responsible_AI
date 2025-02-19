# Responsible_AI
Course work for  Responsible AI [AI&amp;DS-302]

## Assignment 1

"Proxy features" in AI ethics are known as the hidden biases in data which the model learns and uses in the predictions or outcomes. Even if an AI model does not explicitly incorporate protected characteristics such as race, gender, or income, it can make use of other data points-colour discrimination, which would indirectly represent these characteristics-such as ZIP codes, job titles, or buying behaviour.

This project analyzes loan approval data, aiming to understand feature importance and mitigate potential biases.  It begins by preprocessing the data, including handling missing values and converting categorical features to numerical ones.  Variance Inflation Factor (VIF) is used to detect and address multicollinearity, identifying proxy variables that might introduce bias. Feature importance is then assessed using a Decision Tree Regressor and R-squared values, revealing the predictive power of each feature. The analysis identifies "Credit_History" as the most influential factor, while others may be proxy variables requiring further investigation to ensure fairness and transparency. 
