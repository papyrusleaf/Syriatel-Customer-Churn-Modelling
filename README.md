# Syriatel-Customer-Churn-Modelling

This project focuses on developing a model to predict whether a customer is likely to churn from SyriaTel, a telecommunications company. The goal is to help SyriaTel reduce churn by identifying high-risk customers and applying targeted retention strategies. By analyzing customer data, the model provides actionable insights to stakeholders aiming to minimize churn and prevent revenue loss. The results enable SyriaTel to identify at-risk customers and take proactive steps to retain them, supporting efforts to improve customer loyalty and profitability. 

In our modelling, we find that:
- Logistic Regression (both the standard and tuned versions) performs reasonably well with high accuracy and AUC but struggles to identify churners effectively due to low recall. It is more reliable for general classification but not optimal for predicting churn, where recall is crucial.

- Logistic Regression (SMOTE) demonstrates a good improvement in recall, but at the cost of low precision and accuracy. It is suitable if the goal is to catch as many churners as possible, even if that means misclassifying more non-churn customers.

- Decision Tree (and its tuned version) provides a solid balance of precision, recall, and F1-score. Its accuracy and performance make it a better choice for predicting churn compared to logistic regression, especially when fine-tuned.

Overall, the tuned decision tree model provides the best choice given these comparisions

Syriatel is recommended as follows:

- Prioritize Decision Tree (Tuned): Use this model for accurate churn predictions and targeted retention strategies.

- Implement Proactive Retention: Use insights from the churn model to offer personalized promotions and loyalty programs to high-risk customers.

- Leverage SMOTE for Increased Recall: Consider using Logistic Regression (SMOTE) for a higher recall rate to catch more churners, while managing precision.

- Segment Customers: Tailor retention efforts by segmenting customers based on usage patterns, tenure, or demographics for more effective interventions.

- Regular Model Updates: Continuously monitor and update models with new data to maintain accuracy and adapt to changing customer behaviors
