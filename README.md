# handwritten-digits-recognition-ml
Handwritten digit recognition project using traditional machine learning algorithms (SVM, KNN, Logistic Regression) to classify digits from the MNIST dataset.
# 🧠 Handwritten Digits Recognition using Traditional Machine Learning

This project focuses on recognizing handwritten digits (0–9) using **classical machine learning algorithms** such as Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Logistic Regression. The model is trained and evaluated on the popular **MNIST dataset**.

---

## 📌 Project Overview

The goal of this project is to build and compare the performance of traditional ML models for handwritten digit classification without using deep learning frameworks. It demonstrates how classical approaches can still achieve high accuracy on image classification tasks through effective preprocessing and feature extraction.

---

## 🚀 Key Steps

1. **Data Loading & Exploration**  
   - Used MNIST dataset (handwritten digits).  
   - Visualized sample images and distribution of labels.

2. **Preprocessing**  
   - Normalized pixel values.  
   - Flattened 28×28 images into 784 feature vectors.

3. **Model Training**  
   - Trained multiple models:  
     - Support Vector Machine (SVM)  
     - K-Nearest Neighbors (KNN)  
     - Logistic Regression  

4. **Model Evaluation**  
   - Calculated accuracy, confusion matrix, and classification report.  
   - Compared model performances visually.

5. **Result Visualization**  
   - Displayed predictions on sample test images.

---

## 🧰 Tech Stack

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📈 Results

| Model | Accuracy |
|--------|-----------|
| SVM | ~97–98% |
| KNN | ~96% |
| Logistic Regression | ~92% |

> ✅ SVM achieved the highest accuracy on the test dataset.

---

## 📂 Project Files

| File | Description |
|------|--------------|
| `HandwrittenDigits_Project_TraditionalML.ipynb` | Main Jupyter Notebook with code, analysis, and results. |

---

## 🏁 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/handwritten-digits-recognition-ml.git
