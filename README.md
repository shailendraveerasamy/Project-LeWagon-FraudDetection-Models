I created this repository following our team project at Le Wagon (https://github.com/shailendraveerasamy/Project-AI-Financial-Risk-Management).
The goal of the project was to have the best model that is able to detect 90% of fraudulent transactions.

Here are the three models that I tested:
- CatBoostClassifier
- RandomForestClassifier
- LogisticRegression
  
With CatBoostClassifier, we have PR-AUC score: 0.9499. After threshold ajustment, we have Accuracy: 0.9981, Precision: 0.7923, Recall: 0.9174.

With RandomForestClassifier, we have PR-AUC score: 0.8598. After threshold ajustment, we have Accuracy: 0.9964, Precision: 0.6447, Recall: 0.8411.

With LogisticRegression, we have PR-AUC score: 0.2332. After threshold ajustment, we have Accuracy: 0.8565, Precision: 0.0364, Recall: 0.8917.

The model that produces the best results is CatBoostClassifier.
