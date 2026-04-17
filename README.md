# ML Classification Project: Titanic Survival Prediction

### Goal
To predict passenger survival using supervised machine learning.

### Data Preprocessing
- Filled missing 'Age' values with the median.
- Converted 'Sex' into numerical format (Encoding).
- Selected features: Pclass, Age, SibSp, Parch, and Sex.

### Model Comparison

| Algorithm | Accuracy | F1-Score |
| :--- | :--- | :--- |
| Logistic Regression | 80% | 0.74 |
| Random Forest | 82% | 0.77 |

### Conclusion
The Random Forest model is the better choice for this task as it handles the data complexity more effectively, resulting in higher accuracy and F1-scores.
