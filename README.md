# Brain-Tumor-Detection-Using-Deep-Learning

This repository contains a Jupyter Notebook for classifying brain MRI scans into four categories: **No Tumor, Meningioma, Pituitary Tumor, and Glioma**. It uses **VGG16 transfer learning**, **data augmentation**, and **Keras Tuner** for hyperparameter optimization, achieving high accuracy in medical imaging classification.

---

## 📜 Project Overview

- **Dataset**: The Brain Tumor MRI Dataset is included in this repository under the `dataset` folder.
- **Techniques Used**:
  - Transfer Learning with **VGG16**.
  - Data augmentation for robust training.
  - Hyperparameter tuning using **Keras Tuner**.
- **Output**:
  - Trained model saved as `fine_tuned_model.h5`.
  - Training and validation visualizations.

---

## 📥 Downloads

### 1. Pretrained Model
Download the pretrained `.h5` model here:  
[Download Pretrained Model](https://brain-tumor-model-storage.s3.us-east-1.amazonaws.com/fine_tuned_model.h5)

### 2. Dataset
Download the dataset used in this project here:  
[Download Dataset](https://brain-tumor-model-storage.s3.us-east-1.amazonaws.com/Dataset.zip)

---

## 🛠️ Setup and Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.7+
- TensorFlow 2.x
- Keras Tuner
- Jupyter Notebook
  
---

## 🔬 Key Features

### Dataset:
- Images are categorized into subfolders based on classes.

### Data Preprocessing:
- Images are rescaled to `[0, 1]`.
- Data augmentation includes rotation, flipping, and zooming.

### Model Training:
- Fine-tunes **VGG16** for classification.
- Optimized with **Keras Tuner** for best hyperparameters.

### Evaluation:
- Training and validation metrics are visualized.
- Final test accuracy and loss are reported.

---

## 🎨 Results

- **Training Accuracy**: *100.00%*
- **Validation Accuracy**: *92.97%*
- **Test Accuracy**: *93.99%*
  
---

### Clone the Repository

```bash
git clone https://github.com/your-username/brain-tumor-detection-using-deep-learning.git
cd brain-tumor-detection-using-deep-learning
