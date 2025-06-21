# Wine Quality Binary Classification

This project explores binary classification of red wine quality based on physicochemical features using **logistic regression** and **support vector machines (SVMs)**.

## Dataset
- Source: [UCI ML Red Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- Original target: Quality scores (0–10)
- Modified target: Binary labels (1 if quality ≥ 6.5, else 0)

## Models Used
- Logistic Regression
  - Class balancing
  - Threshold tuning
- Support Vector Machine (SVM)
  - RBF and polynomial kernels
  - F1 score used to optimize decision boundary

## Key Metrics (Best Model)
- **Recall (Class 1)**: ~58%
- **Precision (Class 1)**: ~45%
- **Best Model**: SVM with polynomial kernel (degree = 2)

## Techniques Explored
- Class imbalance handling
- Threshold optimization using F1 score
- Evaluation via precision–recall curves
- Kernel selection (RBF vs polynomial)

## Future Work
- Test tree-based models (e.g., random forest, gradient boosting)
- Perform hyperparameter tuning with cross-validation

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Files
- `wine_quality_binary_classification.ipynb`: Final notebook