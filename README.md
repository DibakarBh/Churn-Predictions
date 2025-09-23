In this project, both Logistic Regression (Logit) and Random Forest (RF) models were
evaluated for their ability to predict customer churn. The evaluation metrics included
accuracy, AUC (Area Under the ROC Curve), precision, recall, and overall interpretability.
Below is a detailed comparison of their performance

Accuracy
• Logistic Regression: 74.47%
• Random Forest: 79.88%
• Random Forest provides a higher accuracy (79.88%) compared to Logistic Regression (74.47%).
• Random Forest also has better sensitivity (82.54% vs. 74.60%) and specificity
(77.17% vs. 74.34%).
• Logistic Regression has a more interpretable model with coefficients that show the
effect of each feature on the predicted probability of churn.
• Random Forest outperforms Logistic Regression in terms of accuracy, reflecting its
ability to handle complex patterns and interactions in the dataset more effectively.

AUC (Area Under the Curve)
• Logistic Regression: 0.802
• Random Forest: 0.861
The AUC measures the model's ability to distinguish between churners and non-
churners. A higher AUC for Random Forest indicates better discriminatory power, making
it the stronger classifier overall.

Precision
• Logistic Regression: 74.19%
• Random Forest: 78.64%
Precision measures how many of the predicted churn cases were actual churners.
Random Forest demonstrates higher precision, reducing the likelihood of false positives
(predicting churn for non-churners).

Recall (Sensitivity)
• Logistic Regression: 74.34%
• Random Forest: 82.54%
Recall measures the model's ability to correctly identify actual churners. Random Forest
significantly outperforms Logistic Regression, showcasing its strength in identifying
churners more reliably.

Interpretability
Logistic Regression provides interpretable coefficients for each predictor, allowing for
easy identification of variables driving churn. This is useful for deriving actionable
insights.
Random Forest, on the other hand, excels in predictive performance but lacks the
interpretability of Logistic Regression. Feature importance in Random Forest offers some
insights but is less intuitive than regression coefficients.

Key Trade-Offs
1. Performance:
Random Forest is better suited for predictive tasks where accuracy and recall are
paramount, as demonstrated by its superior metrics across accuracy, precision, and
recall.

2. Interpretability:
Logistic Regression is preferred when understanding the relationships between
variables and churn is important. Its coefficients provide direct, actionable insights
that aid in strategic decision-making.

While Logistic Regression offers simplicity and interpretability, Random Forest delivers
significantly better performance across all key metrics, particularly in accuracy, AUC,
and recall. Depending on the use case, a trade-off can be made between the
explainability of Logistic Regression and the predictive power of Random Forest.
However, for this project’s focus on customer retention, Random Forest emerges as the
more suitable model due to its superior ability to predict churn accurately.
