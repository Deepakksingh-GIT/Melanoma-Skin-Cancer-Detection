## Problem Statement
### Melanoma Skin Cancer Detection

A deep learning project that uses **Convolutional Neural Networks (CNNs)** to detect melanoma from dermoscopic skin images. The goal is to assist in early diagnosis of skin cancer by classifying lesions as benign or malignant.

---
In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.

## Dataset
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.

## 📌 Features
- Preprocessing of dermoscopic images (rescaling, augmentation, normalization).
- CNN model built with **TensorFlow/Keras**.
- Training/validation split using `ImageDataGenerator`.
- Evaluation with accuracy, precision, recall, and F1-score.
- Potential integration into healthcare workflows for early detection.

---

## 📂 Dataset
- Source: "  https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view" dataset path.
- Training/Validation split: 80/20.
- Preprocessing: rescaling, rotation, zoom, horizontal flip.

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Deepakksingh-GIT/Melanoma-Skin-Cancer-Detection.git
cd Melanoma-Skin-Cancer-Detection
pip install -r requirements.txt
