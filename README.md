# 🧠 Handwritten Digit Recognition using Support Vector Machine (SVM)

A machine learning project that classifies handwritten digits (0–9) using **Support Vector Machine (SVM)** models trained on the **MNIST dataset**.  
The project demonstrates data preprocessing, model training, hyperparameter optimization, and result evaluation — all implemented in **Python** using **scikit-learn**.

---

## 🚀 Project Overview

The **goal** of this project is to build a robust digit recognition system capable of identifying handwritten digits from grayscale images.  
By leveraging **SVMs**, the project highlights the power of linear and non-linear kernels for image classification tasks.

---

## 🧩 Dataset

- **Source:** [MNIST Dataset on Kaggle](https://www.kaggle.com/competitions/digit-recognizer)
- **Files Used:**
  - `train.csv` → Contains 42,000 labeled images (28×28 pixels)
  - `test.csv` → Contains 28,000 unlabeled images for prediction
- **Each image:**  
  - Flattened into a 784-dimensional feature vector (28×28 pixels)
  - Labels range from **0 to 9**

---

## ⚙️ Project Workflow

### 1. **Environment Setup**
A virtual environment is created and dependencies are installed via `requirements.txt`:
```bash
pip install -r requirements.txt
