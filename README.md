# Handwritten Digit Recognition using Artificial Neural Network (ANN)

## 📌 Project Overview
This project implements a **Handwritten Digit Recognition System** using an **Artificial Neural Network (ANN)** trained on the famous **MNIST dataset**.  
The model is built using **TensorFlow/Keras** and achieves approximately **98.27% test accuracy**.

The project demonstrates:
- Data preprocessing
- ANN model building
- Regularization techniques
- Model training with callbacks
- Performance evaluation
- Confusion matrix visualization
- Classification report generation

---

## 📂 Dataset
The project uses the **MNIST Handwritten Digits Dataset**, which contains:

- **60,000** training images
- **10,000** testing images
- Grayscale images of size **28×28**
- Digits from **0–9**

Dataset is automatically loaded using:

```python
keras.datasets.mnist.load_data()
