# Support Vector Machines (SVM) - Classification

## 📌 Objective
Implement Support Vector Machines (SVM) for **linear and non-linear classification** using the Breast Cancer dataset.

## 🛠 Tools & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## 🚀 Steps Implemented
1. **Data Preparation**: Loaded Breast Cancer dataset, encoded target labels (M=1, B=0), and scaled features.
2. **Linear SVM**: Trained and evaluated an SVM with a linear kernel.
3. **RBF SVM**: Trained and evaluated an SVM with an RBF kernel.
4. **Hyperparameter Tuning**: Used GridSearchCV to optimize parameters (`C`, `gamma`).
5. **Cross-validation**: Evaluated model robustness with k-fold cross-validation.
6. **Visualization**: Reduced features to 2D using PCA and plotted decision boundaries.

## 📊 Results
- Achieved strong performance with both linear and RBF kernels.
- GridSearchCV provided the best parameters for optimized performance.
- PCA-based visualization showed clear decision boundaries between classes.

## 📈 Example Output
- **Classification Report** with precision, recall, and F1-score.
- **Best Hyperparameters** from GridSearch.
- **Cross-validation Accuracy** scores.
- **Decision Boundary Plot** using PCA-reduced features.

---
✅ This project demonstrates how to apply **SVMs for binary classification**, tune hyperparameters, and visualize decision regions effectively.
