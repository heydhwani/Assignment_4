# Evaluation Summary

## Model Performance Comparison

| Model | Accuracy | F1 Score |
|--------|---------:|---------:|
| Logistic Regression | 78.17% | 78.62% |
| K-Nearest Neighbors (KNN) | 80.28% | 80.00% |
| Random Forest | 88.03% | 89.03% |

## Confusion Matrix Summary

### Logistic Regression
- Correct Predictions: 111
- Incorrect Predictions: 31

### K-Nearest Neighbors (KNN)
- Correct Predictions: 114
- Incorrect Predictions: 28

### Random Forest
- Correct Predictions: 125
- Incorrect Predictions: 17

Random Forest produced the fewest misclassifications and the highest number of correct predictions.

---

## Model Complexity vs Interpretability

- **Logistic Regression**
  - Simple and easy to interpret.
  - Fast to train.
  - Provides a good baseline model.

- **K-Nearest Neighbors (KNN)**
  - More flexible than Logistic Regression.
  - Predictions depend on nearby data points.
  - Harder to interpret because no explicit model is learned.

- **Random Forest**
  - Most complex among the three models.
  - Uses multiple Decision Trees and majority voting.
  - Highest prediction accuracy but lower interpretability compared to Logistic Regression.

---

## Conclusion

Among all the models, **Random Forest** achieved the best performance with **88.03% Accuracy** and **89.03% F1 Score**. It made the fewest prediction errors and provided the most reliable classification for predicting student exam Pass/Fail.

Therefore, **Random Forest** was selected as the final model for this classification task.