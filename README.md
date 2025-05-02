# KNN
# K-Nearest Neighbors (KNN) Classification

This project demonstrates how to implement a K-Nearest Neighbors (KNN) classifier using the Iris dataset from `sklearn`. It includes feature normalization, model training with various values of `k`, evaluation using accuracy and confusion matrix, and visualization of decision boundaries.

---

## 📁 Dataset

- **Dataset used**: Iris Dataset (from `sklearn.datasets`)
- **Features selected**: First two features (Sepal Length and Sepal Width)
- **Target classes**: Setosa, Versicolor, Virginica

---

## 📌 Steps

1. **Load and normalize the dataset**
2. **Split data** into training and testing sets
3. **Train the KNN classifier** using different values of K (e.g., 1, 3, 5, 7, 9)
4. **Evaluate model** performance using:
   - Accuracy Score
   - Confusion Matrix
5. **Visualize decision boundaries** in 2D space for selected K

---

## 🛠️ Requirements

- Python 3.x
- NumPy
- scikit-learn
- matplotlib

You can install the required libraries with:

```bash
pip install numpy matplotlib scikit-learn
