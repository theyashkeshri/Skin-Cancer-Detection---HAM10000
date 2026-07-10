# 🩺 Skin Cancer Detection using EfficientNet-B5 CNN

> A Deep Learning-based Skin Lesion Classification System using **EfficientNet-B5** and the **HAM10000 (Harvard Dataverse)** dataset for early detection of skin cancer.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📖 Project Overview

Skin cancer is one of the most common forms of cancer worldwide, and **early diagnosis significantly increases treatment success rates**. This project develops a **Convolutional Neural Network (CNN)** using **EfficientNet-B5** with transfer learning to classify dermoscopic images into **seven different skin lesion categories**.

The model is trained on the **HAM10000 (Human Against Machine with 10,000 Training Images)** dataset and utilizes image preprocessing, data augmentation, and fine-tuning to achieve high classification performance. The HAM10000 dataset contains 10,015 dermoscopic images across seven diagnostic categories and is widely used for academic research in skin lesion classification. :contentReference[oaicite:0]{index=0}

> **Note:** This project is intended for **research and educational purposes only** and is **not a substitute for professional medical diagnosis.**

---

# 🎯 Objectives

- Detect different types of skin lesions automatically
- Improve diagnostic accuracy using transfer learning
- Reduce manual diagnosis time
- Demonstrate the effectiveness of EfficientNet-B5 for medical image classification

---

# 📂 Dataset

## HAM10000 Dataset

**Dataset Name**

Human Against Machine with 10,000 Training Images (HAM10000)

**Source**

Harvard Dataverse

**Dataset Size**

- 10,015 Dermoscopic Images
- 7 Skin Lesion Classes

The dataset contains expert-labeled dermoscopic images collected from multiple clinical sources and includes pathology-confirmed diagnoses for many cases. :contentReference[oaicite:1]{index=1}

---

## 🧬 Skin Lesion Classes

| Class | Disease |
|--------|----------|
| akiec | Actinic Keratoses |
| bcc | Basal Cell Carcinoma |
| bkl | Benign Keratosis |
| df | Dermatofibroma |
| mel | Melanoma |
| nv | Melanocytic Nevi |
| vasc | Vascular Lesions |

---

# 🏗 Project Architecture

```
HAM10000 Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Image Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
EfficientNet-B5
(Transfer Learning)
        │
        ▼
Fine Tuning
        │
        ▼
Prediction
        │
        ▼
Performance Evaluation
```

---

# 🧠 Model

## EfficientNet-B5

EfficientNet-B5 is a state-of-the-art Convolutional Neural Network that balances:

- Network Depth
- Width
- Image Resolution

using **Compound Scaling**, allowing it to achieve high accuracy with fewer parameters than many traditional CNN architectures.

### Why EfficientNet-B5?

- High classification accuracy
- Faster convergence
- Lower computational cost
- Excellent transfer learning performance
- Suitable for medical imaging tasks

---

# ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-Learn
- Google Colab / Jupyter Notebook

---

# 🔄 Workflow

1. Load HAM10000 Dataset
2. Image Preprocessing
3. Data Augmentation
4. Label Encoding
5. Train-Test Split
6. Build EfficientNet-B5 Model
7. Transfer Learning
8. Fine-Tuning
9. Model Training
10. Performance Evaluation
11. Prediction

---

# 📊 Evaluation Metrics

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- ROC Curve
- Loss Curve
- Accuracy Curve

---

# 📈 Sample Results

Example evaluation outputs include:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Confusion Matrix
- Classification Report
- ROC-AUC Score

*(Replace these with your actual experimental results.)*

---

# 📁 Project Structure

```
Skin-Cancer-Detection/
│
├── dataset/
│   ├── HAM10000_images/
│   ├── metadata.csv
│
├── notebooks/
│   ├── Skin_Cancer_Detection.ipynb
│
├── models/
│   ├── efficientnet_b5.keras
│
├── images/
│   ├── sample_predictions.png
│   ├── confusion_matrix.png
│   ├── accuracy_plot.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Skin-Cancer-Detection.git
```

Move into the project folder

```bash
cd Skin-Cancer-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

```bash
python train.py
```

or

```bash
jupyter notebook
```

Open:

```
Skin_Cancer_Detection.ipynb
```

---

# 📸 Sample Predictions

| Original Image | Predicted Class |
|----------------|-----------------|
| Image 1 | Melanoma |
| Image 2 | Benign Keratosis |
| Image 3 | Basal Cell Carcinoma |

*(Add screenshots after training.)*

---

# 📊 Future Improvements

- Deploy using Streamlit
- Build a Flask/FastAPI REST API
- Mobile application integration
- Explainable AI using Grad-CAM
- Hyperparameter optimization
- Ensemble learning
- Multi-model comparison

---

# 📚 References

- HAM10000 Dataset (Harvard Dataverse) :(https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)
- EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks
- TensorFlow Documentation

---

# ⚠️ Disclaimer

This project is developed solely for **academic and research purposes**. The predictions generated by this model should **not** be used as medical advice or as a replacement for professional dermatological diagnosis.

---

# 👨‍💻 Author

**Yash Keshri**

AI & Machine Learning | Data Science | Deep Learning

- GitHub: https://github.com/theyashkeshri
- LinkedIn: (https://www.linkedin.com/in/theyashkeshri/)

---

## ⭐ If you found this project useful, consider giving it a Star!
```
