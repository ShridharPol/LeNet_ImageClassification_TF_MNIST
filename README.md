# LeNet-Based Image Classification on MNIST and CIFAR-10

This repository contains two well-documented Jupyter notebooks implementing the **LeNet-5 convolutional neural network architecture** using **TensorFlow/Keras** for:

- **MNIST**: Handwritten digit classification
- **CIFAR-10**: Object classification across 10 categories (e.g., airplane, cat, ship)

These projects demonstrate model design, training workflows, and evaluation methods on datasets of increasing complexity.

---

## 📁 Contents

- `LeNet_MNIST.ipynb`: Implements LeNet on the MNIST dataset using TensorFlow and Keras
- `LeNet_CIFAR-10.ipynb`: Extends LeNet to handle CIFAR-10 images with added preprocessing and optimization techniques

---

## 🔧 Key Features

### ✅ MNIST Notebook
- LeNet-5 CNN for digit classification (28×28 grayscale images)
- Data normalization and reshaping
- Training loop with Keras fit method
- Accuracy evaluation and test-time prediction on real input

### ✅ CIFAR-10 Notebook
- Modified LeNet architecture for 32×32 RGB input
- Uses `ImageDataGenerator` for augmentation
- Optimizer experiments: Adam, RMSProp, SGD
- In-depth notes on training curve stability, accuracy fluctuations, and generalization

---

## 🧠 What I Learned
- CNN architecture design and limitations on complex datasets
- Using optimizer choice and augmentation to improve training stability
- Observing overfitting through curve behavior
- Balancing validation performance vs. raw accuracy

---

## 🛠 Tools & Libraries
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

Clone the repo and open either notebook:

```bash
git clone https://github.com/ShridharPol/LeNet_ImageClassification_TF.git
cd LeNet_ImageClassification_TF
jupyter notebook


