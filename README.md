# 🧠 Image Classification using a Convolutional Neural Network (CNN)

## 📖 Overview

This project implements a **Convolutional Neural Network (CNN)** from scratch using **PyTorch** to classify images from the **CIFAR-10** dataset.

The project demonstrates the complete deep learning workflow, including:

* Data preprocessing
* Building a CNN architecture
* Model training
* Model evaluation
* Image prediction on unseen test data

The objective was to understand the core concepts behind CNNs rather than relying on pre-trained models.

---

# 🚀 Features

* Custom CNN built using PyTorch
* Trained on the CIFAR-10 dataset
* Image preprocessing using `torchvision.transforms`
* Convolution, ReLU, and MaxPooling layers
* Fully Connected classifier
* Test accuracy evaluation
* Prediction on unseen images

---

# 🛠️ Tech Stack

* Python
* PyTorch
* Torchvision
* Matplotlib

---

# 📂 Dataset

The project uses the **CIFAR-10** dataset.

### Dataset Information

* **60,000 RGB images**
* **10 classes**
* **32 × 32 image size**
* **50,000 training images**
* **10,000 testing images**

Classes:

* ✈️ Airplane
* 🚗 Automobile
* 🐦 Bird
* 🐱 Cat
* 🦌 Deer
* 🐶 Dog
* 🐸 Frog
* 🐴 Horse
* 🚢 Ship
* 🚚 Truck

---

# 🧠 CNN Architecture

Input Image

**3 × 32 × 32**

⬇️

**Conv2D**

* Input Channels: 3
* Output Channels: 32
* Kernel Size: 3 × 3
* Padding: 1

⬇️

ReLU

⬇️

MaxPool2D (2 × 2)

⬇️

**Conv2D**

* 32 → 64 Channels

⬇️

ReLU

⬇️

MaxPool2D (2 × 2)

⬇️

**Conv2D**

* 64 → 128 Channels

⬇️

ReLU

⬇️

MaxPool2D (2 × 2)

⬇️

Flatten

⬇️

Fully Connected Layer

⬇️

Output Layer (10 Classes)

---

# 📊 Results

**Test Accuracy:**

75.16%

---

# 🔍 Sample Prediction

Example output:

```text
Actual: Cat
Predicted: Cat
```

The model can successfully classify unseen images from the test dataset after training.

---

# 📚 Concepts Learned

This project covers:

* Convolutional Neural Networks (CNNs)
* Feature Maps
* Kernels (Filters)
* Padding
* Stride
* ReLU Activation
* Max Pooling
* Flattening
* Fully Connected Layers
* Forward Propagation
* Cross Entropy Loss
* Backpropagation
* Gradient Descent
* Model Evaluation
* Accuracy Calculation

---

# 📁 Project Structure

```text
├── train.py
├── model.py
├── README.md
├── requirements.txt
└── data/
```

---

# ▶️ Installation

Install the dependencies:

```bash
pip install torch torchvision matplotlib
```

---

# 🔮 Future Improvements

* Data augmentation
* Batch Normalization
* Dropout layers
* Learning rate scheduling
* Hyperparameter tuning
* Transfer learning using ResNet or EfficientNet
* Confusion matrix visualization
* Training and validation loss graphs
* Multiple image prediction visualization

---

# 👩‍💻 Author

Developed as a deep learning project to understand the implementation of Convolutional Neural Networks using PyTorch.

If you found this project helpful, feel free to ⭐ the repository.
