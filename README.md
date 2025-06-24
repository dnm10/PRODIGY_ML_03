# PRODIGY_ML_03
# Dogs🐶 vs Cats🐱 Image Classification with SVM
This project implements a Support Vector Machine (SVM) model to classify images of cats and dogs using the [Kaggle Dogs VS Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data).

---

## 🎯 Objective

To build a binary image classifier using SVM that distinguishes between cats and dogs. This involves image preprocessing, feature extraction, and training a classical machine learning model.

---

## 📁 Overview

- Download and preprocess the dataset from Kaggle

- Resize and flatten images to extract numerical features

- Train a Support Vector Machine (SVM) on the extracted features

- Evaluate the classifier using accuracy and confusion matrix

- Visualize sample predictions

---

## 🧠 Model Overview

- **Algorithm**: Support Vector Machine (SVM)
- **Framework**: Scikit-learn
- **Evaluation Metric**: Accuracy, Confusion Matrix
- **Tools**: Python, NumPy, OpenCV, Matplotlib, Scikit-learn

---

## ⚙️ Preprocessing Pipeline

- Resize all images to a fixed size (e.g., 64×64 pixels)

- Convert to grayscale (optional for faster training)

- Flatten images into 1D vectors

- Normalize pixel values (0–1)

---

## 🧪 Training Details

- Use a subset of the dataset for faster training (e.g., 1000 cat + 1000 dog images)

- Apply train_test_split() to create training and testing sets

- Train an SVM classifier (sklearn.svm.SVC) with a linear or RBF kernel

---

## 📊 Results

- ✅ Accuracy Score: ~90% (depending on subset and kernel)

- 📉 Confusion Matrix: Shows correct and misclassified labels

- 🖼️ Sample Predictions: Visualize correctly/incorrectly classified images


These insights can help businesses target specific customer segments more effectively.

---

## Author

- [@dnm10](https://github.com/dnm10)
