# VGG16 Applications in Water Turbidity and Waste Classification
# Water and Waste Classification Using VGG16

## Overview

This project uses the VGG16 convolutional neural network (CNN) architecture combined with transfer learning to classify:

- Water turbidity levels
- Waste categories

The model was implemented using TensorFlow and trained on Google Colab with GPU support.

---

## Water Turbidity Classes

- Turbidity 0.1
- Turbidity 0.2
- Turbidity 0.3
- Turbidity 0.4
- Turbidity 0.5

---

## Waste Classification Classes

- Organic Waste
- Inorganic Waste
- Hazardous Waste
- Recyclable Waste

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Google Colab
- OpenCV
- NumPy
- Matplotlib

---

## Model Architecture

### Base model

- VGG16 (pre-trained on ImageNet)

### Removed layers

- Flatten
- Fully connected layer (4096)
- Fully connected layer (4096)
- Softmax layer (1000 classes)

### Added layers

- Flatten
- Dense (128, ReLU)
- Dropout (0.5)
- Dense (Softmax)

---

## Training Techniques

- Transfer Learning
- Data Augmentation
- Early Stopping

---

## Dataset Information

### Water turbidity dataset

| Dataset | Images |
|----------|---------|
| Train | 240 |
| Validation | 20 |
| Test | 25 |

### Waste classification dataset

| Dataset | Images |
|----------|---------|
| Train | 1000 |
| Validation | 148 |
| Test | 152 |

---

## Results

### Water turbidity classification

Accuracy: 92%

### Waste classification

Accuracy: 90.13%

---

## Author

University of Transport Technology (UTT)

Department of Information Systems
