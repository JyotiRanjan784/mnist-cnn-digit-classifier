# 🧠 MNIST CNN Digit Classifier

## 📌 Project Overview

This project builds a **Convolutional Neural Network (CNN)** to classify handwritten digits (0–9) using the MNIST dataset.
It demonstrates the complete deep learning workflow including preprocessing, training, evaluation, and visualization.

---

## 🚀 Features

* Data preprocessing (normalization & reshaping)
* CNN model architecture
* Training with callbacks (EarlyStopping & ReduceLROnPlateau)
* Model evaluation on test data
* Visualization (accuracy, loss, confusion matrix)
* Model saving for reuse

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

* **MNIST Dataset**

  * 60,000 training images
  * 10,000 test images
  * Image size: 28x28 (grayscale)

---

## ⚙️ Workflow

### 🔹 Task 1: Data Preparation

1. Import required libraries
2. Load MNIST dataset
3. Normalize pixel values
4. Reshape data for CNN
5. Apply one-hot encoding

---

### 🔹 Task 2: Model & Evaluation

6. Build CNN model
7. Train model with callbacks
8. Evaluate test accuracy
9. Generate predictions
10. Confusion matrix
11. Accuracy graph
12. Loss graph
13. Display sample prediction
14. Save trained model

---

## 📊 Output Files

The following images are generated during execution:

* `sample_image.png`
* `accuracy.png`
* `loss.png`
* `confusion_matrix.png`
* `predictions.png`
* `model_structure.png`

---

## 🧪 Model Performance

* Training Accuracy: ~99%
* Test Accuracy: ~98–99%

---

## 💾 Model File

```
mnist_cnn_model.h5
```

---

## ▶️ How to Run

1. Install dependencies:

```
pip install tensorflow numpy matplotlib seaborn scikit-learn
```

2. Run the file:

```
mnist_cnn_digit_classifier.ipynb
```

---

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Try deeper architectures
* Deploy as web application
* Apply on other datasets

---

## 👨‍💻 Author

Jyoti Ranjan Barik

---

If you like this project, give it a ⭐ on GitHub!
