# Wine_quality
Predicting Portuguese wine quality using Logistic Regression, Random Forest, and Gradient Boosting

The Wine Quality dataset was chosen because it contains multiple features with real-world significance. Predicting wine quality from chemical properties demonstrates practical applications of classification algorithms and allows us to explore data preprocessing, modeling, and interpretability techniques, which are critical skills in machine learning

EDA basic summary: 
No missing values
All features are numeric
1599 samples, 11 features + target

For target distribution imbalances exist which is addressed in modeling

Key correlations:
Alcohol positively correlates with quality
Volatile acidity negatively correlates
Density slightly negatively correlates

Random Forest perfromed the highest accuracy(0.825) and F1-score (0.87), outperforming Gradient Boosting (accuracy 0.759, F1 0.82) and Logistic Regression (accuracy 0.724, F1 0.79). This indicates that the relationships between chemical features and wine quality are nonlinear, which tree-based ensemble methods capture effectively.

Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Wine Quality [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T.
