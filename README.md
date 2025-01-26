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

## 🛠️ Setup and Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.7+
- TensorFlow 2.x
- Keras Tuner
- Jupyter Notebook

### Clone the Repository

```bash
git clone https://github.com/your-username/brain-tumor-detection-using-deep-learning.git
cd brain-tumor-detection-using-deep-learning

