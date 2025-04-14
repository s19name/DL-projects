# Handwritten Digit Recognition using PyTorch

This project uses **PyTorch** and **Convolutional Neural Networks (CNNs)** to recognize handwritten digits from the **MNIST** dataset.

---

##  Dataset

- **Training Set:** 60,000 handwritten digits (0–9) in grayscale  
- **Test Set:** 10,000 handwritten digits (0–9) in grayscale  

---

## Model Architecture

- **2 Convolutional Layers**
- **Dropout Layer**
- **ReLU Activation Functions** (in hidden layers)
- **Softmax Activation** (in the output layer)

---
- The dataset is loaded using `torchvision.datasets.MNIST`
- The model is trained using Cross-Entropy Loss and an optimizer Adam
---

## Result
The final model predicts a digit (0–9) for each input image based on learned features with result of 97.4% on test set.

