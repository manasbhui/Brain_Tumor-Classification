# 🧠 Enhancing Brain Tumor Classification Through Image Subtraction Analysis
📄 **IEEE Published Research | IC-CGU 2025**

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KNN-green)
![Medical Imaging](https://img.shields.io/badge/Medical%20Imaging-MRI-red)
![IEEE Publication](https://img.shields.io/badge/Research-IEEE-success)

A machine learning based system for **brain tumor classification using MRI images** by combining **Local Binary Pattern (LBP)**, **Image Subtraction Analysis**, and **k-Nearest Neighbors (k-NN)**.

---

# 📄 Research Publication

**Paper Title**

Enhancing Brain Tumor Classification Through Image Subtraction Analysis

**Conference**

IEEE International Conference on Cognitive, Green and Ubiquitous Computing (IC-CGU 2025)

📑 IEEE Paper Link  
https://ieeexplore.ieee.org/abstract/document/11338093

---

# 📌 Problem Statement

Brain tumor diagnosis using MRI images is a critical task in medical analysis. Traditional texture extraction methods such as Local Binary Pattern (LBP) are sensitive to noise and may fail to capture complex tumor textures.

This research proposes an improved feature extraction method using **image subtraction** to enhance tumor textures and improve classification accuracy.

---

# 💡 Proposed Solution

The proposed system works by:

1. Extracting **texture features using LBP**
2. Subtracting the **original MRI image from the LBP image**
3. Enhancing **tumor edges and texture patterns**
4. Feeding the processed image features into a **k-NN classifier**

This approach reduces noise and improves tumor feature representation.

---

# 🧬 Tumor Classes

The model classifies MRI images into three tumor types:

- Glioma
- Meningioma
- Pituitary

---

# ⚙️ Methodology Pipeline

MRI Image  
↓  
Grayscale Conversion  
↓  
Local Binary Pattern (LBP)  
↓  
Image Subtraction (LBP − Original Image)  
↓  
Image Resizing (64×64)  
↓  
Normalization  
↓  
Feature Extraction  
↓  
K-Nearest Neighbors (KNN)  
↓  
Brain Tumor Classification

---

# 📊 Dataset

Two publicly available datasets were used:

1. Figshare Brain MRI Dataset  
2. Kaggle Brain Tumor MRI Dataset  

Dataset Characteristics:

- Image size: **512 × 512**
- Classes: **Glioma, Meningioma, Pituitary**
- Training split: **80%**
- Testing split: **20%**

---

# 📈 Results

The proposed model achieved strong classification performance.

| Metric | Value |
|------|------|
| Accuracy | **95.44%** |
| Precision | High |
| Recall | High |
| F1 Score | Balanced |


---

# 🧪 Visual Results

The following figures illustrate the visual outcomes of the proposed brain tumor classification approach.  
These include the original MRI images, LBP-transformed images, texture-differentiated images, and their corresponding histograms.

## Classification Visualization

![Visual](https://github.com/manasbhui/Brain_Tumor-Classification/blob/b223999d5c14de428c874ef5f1934db3353d6774/Visual%20outcome.JPG)

This visualization demonstrates the transformation pipeline:

1. Original MRI Image  
2. LBP Feature Extraction  
3. Texture Differentiation using Image Subtraction  
4. Histogram Analysis of Pixel Distribution

---

## Histogram Analysis

### Glioma Histogram

![glioma Histogram.jpg](https://github.com/manasbhui/Brain_Tumor-Classification/blob/b223999d5c14de428c874ef5f1934db3353d6774/glioma%20Histogram.jpg))

### Meningioma Histogram

![(meningioma histogram.jpg)](https://github.com/manasbhui/Brain_Tumor-Classification/blob/b223999d5c14de428c874ef5f1934db3353d6774/meningioma%20histogram.jpg)

### Pituitary Histogram

![pituitary Histogram.jpg)](https://github.com/manasbhui/Brain_Tumor-Classification/blob/b223999d5c14de428c874ef5f1934db3353d6774/pituitary%20Histogram.jpg)

These histograms represent the **pixel intensity distribution after texture differentiation**, which helps in distinguishing between different tumor types.

---
---

# 🔬 Research Contribution

This project introduces a **novel feature enhancement technique** for brain tumor classification by combining **Local Binary Pattern (LBP)** with **image subtraction analysis**.

The proposed method improves traditional LBP-based approaches by:

- Reducing noise in MRI images
- Enhancing tumor edges and textures
- Improving classification accuracy
- Achieving **95.44% accuracy** in tumor classification

This research demonstrates the potential of combining **image processing and machine learning techniques** for improved medical image analysis.

# 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Image Processing
- Machine Learning

---

# 🚀 Future Improvements

Future work may include:

- Deep Learning models (CNN)
- Transfer Learning
- Data Augmentation
- Hybrid ML + DL architectures
- Real-time medical diagnostic systems

---

# 👨‍💻 Author

**Manas Ranjan Bhui**

B.Tech – Computer Science and Engineering  
CV Raman Global University

Skills

- Machine Learning
- Data Analytics
- Python
- SQL
- Power BI
- Computer Vision

---

⭐ If you found this project useful, please consider giving it a star!
