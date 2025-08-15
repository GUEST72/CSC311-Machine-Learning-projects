# CSC311 - Assignment 2: From Linear Models to Deep Networks

**Course:** Introduction to Machine Learning (CSC311)  
---

## 🎯 Objectives
- Transition from **linear models** to **deep neural networks**.
- Implement models **from scratch** using PyTorch.
- Master PyTorch data handling and custom training loops.
- Conduct systematic hyperparameter and architecture analysis.
- Explore and evaluate advanced regularization techniques.

---

## 📂 Project Structure

### **Part A — Linear Classification Models**
- **Data Preparation:**
  - Download and preprocess MNIST dataset.
  - Normalize pixel values and prepare both flattened and original shapes.
  - Split into train (60%), validation (20%), and test (20%).
  - Create PyTorch DataLoaders.
- **Implementation:**
  - Binary Logistic Regression from scratch (sigmoid activation, binary cross-entropy, SGD).
  - Multi-class Softmax Regression from scratch (softmax activation, cross-entropy).
  - Compare results with PyTorch’s built-in models.
- **Evaluation:**
  - Training and validation loss/accuracy curves.
  - Confusion matrix and per-class accuracy.

---

### **Part B — Neural Networks**
- **Custom Feedforward Architecture:**
  - Input → Hidden1 → Hidden2 → Output with ReLU activations.
  - Xavier/He initialization.
  - Flexible structure for layer/neurons modifications.
- **Training Loop:**
  - Forward pass, backpropagation, weight updates with SGD.
  - Track performance over epochs.
- **Visualization:**
  - Loss curves, accuracy curves, learning curves with error bars.
  - Convergence analysis.

---

### **Part C — Hyperparameter & Model Analysis**
- **Learning Rate Variations:** [0.001, 0.01, 0.1, 1.0]
- **Batch Sizes:** [16, 32, 64, 128]
- **Architectural Depth:** 2–5 hidden layers
- **Neurons per Layer:** [64, 128, 256, 512]
- Comparative study between logistic regression, softmax regression, and best NN model.

---

### **Part D — Advanced Techniques (Bonus)**
- Convolutional Neural Network (CNN) implementation for MNIST.
- Dropout analysis with different rates.
- Batch normalization and combined effects.

---

## 🛠 Tools & Libraries
- Python 3.x
- PyTorch
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-Learn (for baseline comparisons)
