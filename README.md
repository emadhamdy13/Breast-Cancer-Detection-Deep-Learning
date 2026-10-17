# Breast Cancer Classification using Deep Learning

An end-to-end Deep Learning pipeline built with TensorFlow/Keras to classify breast cancer tumors (Malignant vs. Benign).

## 🚀 Key Highlights & Results
- **Test Loss:** 0.0680
- **Test Recall:** 0.9762 (Optimized to minimize False Negatives in medical diagnosis)
- **Data Pipeline:** Handled missing values using `KNNImputer`, capped outliers using the IQR technique, and standardized features.
- **Architecture:** Sequential Neural Network with `ReLU` activations, `Sigmoid` output, and `EarlyStopping` callback to prevent overfitting.

## 🛠️ Tech Stack
- **Python**
- **TensorFlow / Keras**
- **Pandas & NumPy**
- **Scikit-Learn**

## 📊 Model Evaluation
Evaluated on unseen test data using Recall as the primary evaluation metric to ensure high diagnostic reliability.

---
### 📂 Files in this Repository:
- `deep learning project.ipynb`: The complete Google Colab notebook containing data preprocessing, feature engineering, model training, and evaluation.
