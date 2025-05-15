# 💵 Banknote Authentication using Support Vector Machine (SVM)

This repository contains a Google Colab notebook implementing **Support Vector Machine (SVM)** for the task of authenticating banknotes. It uses the **Banknote Authentication Dataset** to classify whether a banknote is genuine or forged based on extracted statistical features.

---

## 📚 Project Description

In this project, we:

- Load and preprocess the Banknote Authentication dataset
- Visualize data distributions and correlations
- Train and evaluate an SVM classifier
- Test the model's performance using standard metrics

---

## 🧠 Dataset Information

- **Name**: Banknote Authentication Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
- **Number of Instances**: 1,372
- **Features**:
  - `variance` of Wavelet Transformed image
  - `skewness` of Wavelet Transformed image
  - `curtosis` of Wavelet Transformed image
  - `entropy` of image
  - `class`: 0 = authentic, 1 = fake

---

## 🧪 Model Used

| Model | Description |
|-------|-------------|
| **SVM (Support Vector Machine)** | A powerful classifier that finds the optimal hyperplane to separate data points. Works well for both linear and non-linear boundaries.|

You may also test with different kernels:
- Linear
- RBF (Radial Basis Function)

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix


## 📌 Requirements

Colab already includes all necessary packages:
- `pandas`, `missingno`
- `matplotlib`, `seaborn`
- `scikit-learn`

No need to install anything manually.

## 🙋 Author

**Baohikari**  
📫 [GitHub Profile](https://github.com/Baohikari)
