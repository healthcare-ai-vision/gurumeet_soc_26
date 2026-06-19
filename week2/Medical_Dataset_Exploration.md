# Medical Imaging Dataset Exploration

This document provides an exploration of two important medical imaging datasets used in machine learning and computer-aided diagnosis.

---

## 1. Chest X-Ray Images (Pneumonia)

### Type of Imaging Data

Anterior-posterior chest X-ray images (JPEG format).

### Number of Images

5,863 images.

### Available Classes or Labels

* Normal
* Pneumonia

The pneumonia category includes both bacterial and viral pneumonia cases.

### Dataset Imbalance

The dataset is imbalanced because it contains significantly more pneumonia images than normal images. This imbalance can cause machine learning models to become biased toward the pneumonia class during training.

### Observed Challenges

* Image quality variations and unreadable scans.
* Differences in patient positioning during X-ray acquisition.
* Need for accurate expert annotation and diagnosis verification.
* Class imbalance between normal and pneumonia cases.

### Brief Summary

This dataset contains pediatric chest X-ray images used for pneumonia detection. It is widely used in medical image classification and deep learning research. The dataset helps researchers develop automated systems that can distinguish between healthy lungs and lungs affected by pneumonia.

---

## 2. HAM10000 Skin Lesion Dataset

### Type of Imaging Data

Dermatoscopic images of pigmented skin lesions.

### Number of Images

10,015 images.

### Available Classes or Labels

The dataset contains seven classes:

1. akiec – Actinic keratoses and intraepithelial carcinoma
2. bcc – Basal cell carcinoma
3. bkl – Benign keratosis-like lesions
4. df – Dermatofibroma
5. mel – Melanoma
6. nv – Melanocytic nevi
7. vasc – Vascular lesions

### Dataset Imbalance

The dataset is highly imbalanced. The melanocytic nevi (nv) class contains significantly more images than minority classes such as dermatofibroma (df) and vascular lesions (vasc). This makes classification of minority classes more challenging.

### Observed Challenges

* Presence of image artifacts such as hairs, gel bubbles, tattoos, and jewelry.
* Images collected from multiple sources over many years.
* Variations in image quality, lighting conditions, and magnification.
* Complex annotation and standardization of diagnostic labels.
* Significant class imbalance.

### Brief Summary

HAM10000 (Human Against Machine with 10,000 training images) is a widely used benchmark dataset for skin lesion classification. It contains a diverse collection of dermatoscopic images representing seven common skin lesion categories. The dataset is extensively used to evaluate and compare machine learning models for dermatological diagnosis.

---

## Sources

1. Chest X-Ray Images (Pneumonia) Dataset – Kaggle
2. Tschandl et al., *The HAM10000 Dataset: A Large Collection of Multi-Source Dermatoscopic Images of Common Pigmented Skin Lesions*, Scientific Data (2018)
