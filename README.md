# 🔍 Logistic Regression from Scratch

This project is a complete, manual implementation of **Logistic Regression**, one of the foundational algorithms in machine learning. The goal of this project is not just to build a classifier, but to deeply understand the mathematical intuition, computational logic, and training process that powers real-world classification models.

---

## 🧠 What is Logistic Regression?

Logistic Regression is a **supervised learning algorithm** used for **binary classification problems**, where the output is either 0 or 1 (e.g., spam or not spam, sick or healthy). Unlike linear regression, which predicts a continuous value, logistic regression predicts **probabilities** using the **sigmoid function** and converts them into binary outcomes based on a threshold.

---

## 🎯 Project Goals

This project was built with the following learning objectives:

- Understand how logistic regression works internally  
- Implement **sigmoid function**, **cost function**, and **gradient descent** from scratch  
- Learn how optimization works through **loss minimization**  
- Visualize the **decision boundary** of the trained classifier  
- Strengthen the ability to debug, tune, and interpret model behavior without libraries like `scikit-learn`

---

## 📌 What This Project Includes

✅ **Manual Implementation** of:  
- Sigmoid activation function  
- Cost function for binary cross-entropy  
- Gradient calculation  
- Parameter updates via gradient descent  
- Decision boundary plotting and accuracy evaluation  

📊 **Training on Datasets**:  
- Applied the model on two different 2D datasets for binary classification tasks  
- Visualized model performance and how decision boundaries evolve

🛠 **Tools Used**:
- Python  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 🚀 How the Model Works

### 1. Sigmoid Function  
The sigmoid function maps real-valued inputs into a range between 0 and 1. It's defined as:  
```math
σ(z) = 1 / (1 + e^{-z})
