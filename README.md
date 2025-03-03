# CNN Image Classification with PyTorch  

This repository contains a Jupyter Notebook demonstrating the implementation of **Convolutional Neural Networks (CNNs)** for image classification tasks using **PyTorch**. The notebook covers foundational concepts, explores different neural network architectures, and evaluates their performance on **MNIST** and **CIFAR-10** datasets.  

## 📌 Features  

### 1. Datasets  
- **MNIST**: A dataset of handwritten digits (grayscale, 28×28).  
- **CIFAR-10**: A dataset of RGB images (32×32) across 10 object classes.  

### 2. Model Architectures  
- **Multi-Layer Perceptron (MLP)**:  
  - Two- and three-hidden-layer fully connected networks to demonstrate MLP limitations for image classification.  
- **Convolutional Neural Networks (CNNs)**:  
  - Simple three-layer CNN optimized for MNIST.  
  - Enhanced CNN with three convolutional layers and pooling layers for CIFAR-10.  

### 3. Core Concepts  
- **Inductive Bias in CNNs**:  
  - Local connectivity, shared weights, and hierarchical feature learning explained.  
- **Overfitting Analysis**:  
  - Experiments on small datasets to analyze overfitting and validate model capacity.  
- **Visualization Tools**:  
  - Training loss, training accuracy, and test accuracy plotted across epochs.  

### 4. Performance Evaluation  
- Baseline accuracy calculations for **MNIST** and **CIFAR-10** datasets.  
- Comparison of **MLP** and **CNN** in terms of training/testing accuracy.  
- Analysis of **parameter efficiency** in CNNs vs. MLPs.  

## 📊 Results  

### **MNIST**  
| Model                   | Test Accuracy |  
|-------------------------|--------------|  
| MLP (Two Hidden Layers) | ~78%         |  
| MLP (Three Hidden Layers) | ~88%       |  
| CNN                     | **~99.05%**  |  

### **CIFAR-10**  
| Model                   | Test Accuracy |  
|-------------------------|--------------|  
| MLP (Three Hidden Layers) | ~43%       |  
| CNN                     | **~73.20%**  |  
