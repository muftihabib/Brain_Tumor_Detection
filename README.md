# Brain Tumor MRI Classification Using Multiple Deep Learning Models

A deep learning project for classifying brain MRI images into four different categories using transfer learning with multiple pre-trained convolutional neural networks.

The project compares four popular deep learning architectures:

- EfficientNetB0
- MobileNetV2
- ResNet50
- DenseNet121

The goal is to evaluate and compare these models using metrics such as Accuracy, Precision, Recall, and F1 Score and identify the best-performing model.

---

## Project Overview

Brain tumors are abnormal growths of cells in the brain that can be difficult to identify accurately.

This project uses brain MRI images and deep learning-based image classification to classify MRI scans into four categories:

1. Glioma
2. Meningioma
3. No Tumor
4. Pituitary

Instead of relying on a single deep learning architecture, multiple pre-trained models are trained and evaluated on the same dataset.

The performance of the models is then compared to determine which architecture performs best for this dataset.

---

## Classes

The model classifies MRI images into:

| Class | Description |
|---|---|
| Glioma | Glioma brain tumor |
| Meningioma | Meningioma brain tumor |
| No Tumor | MRI image without tumor |
| Pituitary | Pituitary tumor |

---

## Dataset

The dataset contains **7,200 MRI images**.

### Dataset Distribution

| Dataset | Images |
|---|---:|
| Training | 5,600 |
| Validation | 1,120 |
| Testing | 1,600 |
| Total | 7,200 |

### Training Dataset

Each class contains approximately 1,400 images:

```text
Training/
├── glioma/
│   └── 1400 images
├── meningioma/
│   └── 1400 images
├── notumor/
│   └── 1400 images
└── pituitary/
    └── 1400 images
