# Brain Tumor Detection System using CNN

## Overview

This project is a Deep Learning-based Brain Tumor Detection System developed using Convolutional Neural Networks (CNNs). The model analyzes MRI brain scans and classifies them into one of four categories:

* Glioma Tumor
* Meningioma Tumor
* Pituitary Tumor
* No Tumor

The system utilizes TensorFlow and Keras to train a CNN model capable of identifying tumor types with high accuracy. By leveraging image preprocessing and data augmentation techniques, the model achieves robust performance and demonstrates the practical application of Artificial Intelligence in medical image analysis.

---

## Features

✅ MRI Brain Scan Classification

✅ Multi-Class Tumor Detection

✅ Data Augmentation for Better Generalization

✅ Confidence Score Prediction

✅ CNN-Based Deep Learning Architecture

✅ TensorFlow & Keras Implementation

✅ Visualization of Prediction Results

✅ Automated Tumor Classification

---

## Dataset Structure

```text
data image/
│
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   └── pituitary/
│
└── Testing/
    ├── glioma/
    ├── meningioma/
    ├── notumor/
    └── pituitary/
```

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* OpenCV
* Pillow
* Deep Learning
* Computer Vision

---

## Model Architecture

The CNN architecture consists of:

* Conv2D (32 Filters, ReLU)
* MaxPooling2D
* Conv2D (64 Filters, ReLU)
* MaxPooling2D
* Conv2D (128 Filters, ReLU)
* MaxPooling2D
* Conv2D (512 Filters, ReLU)
* MaxPooling2D
* Flatten Layer
* Dense Layer (512 Units, ReLU)
* Dropout (0.5)
* Output Layer (4 Classes, Softmax)

---

## Data Augmentation

To improve model generalization and reduce overfitting, the following augmentation techniques were applied:

* Rescaling
* Rotation
* Width Shift
* Height Shift
* Shear Transformation
* Zoom
* Horizontal Flip

---

## Model Performance

| Metric    | Value            |
| --------- | ---------------- |
| Accuracy  | 95.78%           |
| Classes   | 4                |
| Epochs    | 50               |
| Framework | TensorFlow/Keras |

---

## Prediction Output

The trained model predicts:

* Tumor Type
* Confidence Score

### Example Output

```text
Predicted Class: Glioma
Confidence: 99.83%
```

---

## Applications

* Medical Image Analysis
* Healthcare AI Solutions
* Brain Tumor Screening Assistance
* Computer-Aided Diagnosis Systems
* Medical Research and Education
* Deep Learning Research

---

## Future Improvements

* Transfer Learning using EfficientNet or ResNet
* Streamlit Web Application Deployment
* Mobile Application Integration
* Grad-CAM Visualization for Explainable AI
* Real-Time MRI Scan Analysis
* Model Optimization for Faster Inference

---

## Installation

```bash
git clone https://github.com/yourusername/Brain-Tumor-Detection-System-CNN.git

cd Brain-Tumor-Detection-System-CNN

pip install -r requirements.txt
```

---

## Requirements

```text
tensorflow
keras
numpy
matplotlib
opencv-python
pillow
scikit-learn
```

---

## Results

The model successfully classifies MRI brain scans into four categories with an overall accuracy of **95.78%**. Predictions include confidence scores, enabling reliable and interpretable classification results.

---

## Author

### Vijay Krishnan P.M.

---

## License

This project is intended for educational and research purposes.
