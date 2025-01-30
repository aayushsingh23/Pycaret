# Machine Learning Projects with PyTorch and PyCaret

## Overview
This repository contains three projects demonstrating **Machine Learning** techniques using **PyTorch** and **PyCaret**:
1. **Facial Expression Recognition** - Classifies facial expressions using deep learning.
2. **Classification with PyCaret** - Automates ML model selection for classification problems.
3. **Regression with PyCaret** - Automates ML model selection for regression tasks.

---

## 1. Facial Expression Recognition
### Dataset
[Face Expression Recognition Dataset](https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset)

### Implementation Steps
- **Load Dataset**: Resize and normalize images.
- **Define Model**: CNN architecture using PyTorch.
- **Training**: Uses CrossEntropyLoss and Adam optimizer.
- **Evaluation**: Measures accuracy on test data.
- **Results**: Accuracy and predictions visualized with matplotlib.

---

## 2. Classification with PyCaret
### Overview
PyCaret simplifies classification model comparison and selection with minimal code. It supports:
- **Multiple ML Algorithms**
- **Automated Hyperparameter Tuning**
- **Model Deployment**

### Implementation Steps
- **Load Data**
- **Set Up PyCaret Environment**
- **Compare ML Models**
- **Select Best Model**
- **Evaluate Model Performance**

---

## 3. Regression with PyCaret
### Overview
Similar to classification, PyCaret automates model selection for regression tasks.

### Implementation Steps
- **Load Data**
- **Set Up PyCaret Environment**
- **Compare ML Models**
- **Select Best Model**
- **Evaluate Model Performance**

---

## Installation
To run these projects, install the dependencies:
```bash
pip install torch torchvision matplotlib numpy pandas pycaret
```


