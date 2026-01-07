# Generative-Ai-Project
 # 🧠 CNN-Based Medical Image Classification (PathMNIST)

This project implements a **Convolutional Neural Network (CNN)** for **medical image classification** using the **PathMNIST dataset**.  
The work was carried out as part of a **Deep Learning internship at NIT Patna**, focusing on applying CNNs to real-world medical imaging data.

---

## 📌 Project Overview

- **Domain:** Deep Learning / Medical Image Analysis  
- **Model:** Convolutional Neural Network (CNN)  
- **Dataset:** PathMNIST (MedMNIST v2)  
- **Institution:** National Institute of Technology (NIT), Patna  
- **Task:** Multi-class classification of histopathology images  

The objective was to design, train, and evaluate a CNN model that can accurately classify medical images while maintaining good generalization performance.

---

## 🚀 Key Results

- **Training Accuracy:** ~97.5%  
- **Best Validation Accuracy:** **~97.8%**  
- **Final Validation Accuracy:** ~97%  
- **Loss Trend:** Smooth convergence with minimal overfitting  

The close alignment between training and validation accuracy indicates **strong generalization** of the model.

---

## 📊 Performance Visualization

The project includes accuracy and loss curves to analyze model behavior across epochs:

- Accuracy steadily improves and stabilizes around 97–98%
- Validation loss decreases consistently, confirming stable learning

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## ⚙️ Model Architecture (High Level)

- Convolutional layers with ReLU activation
- MaxPooling layers for spatial downsampling
- Fully connected (Dense) layers
- Softmax output layer for multi-class classification

The architecture was tuned to balance accuracy and overfitting control.

---

## ▶️ How to Run

1. Clone the repository:
   ```
   https://github.com/Ankitji001/Generative-Ai-Project.git
   pip install -r requirements.txt
   jupyter notebook


