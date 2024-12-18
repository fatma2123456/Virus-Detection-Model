# Virus-Detection-Model🦠🤖
## 📖 Overview

Welcome to the **Virus Dataset Classification** project! 🎉 This repository explores classifying virus images using deep learning models and compares the performance of different architectures:
- **CNN (Convolutional Neural Network)** 🧠
- **ResNet-50 (Residual Networks)** 🔄
- **DenseNet-201** 💪
- **Xception** 🚀

The project aims to classify virus images from a dataset containing 14 virus classes. The repository includes the code for training and evaluating these models on the virus image dataset.
---
## 🦠 What Are Virus Images? (The Hidden World of Viruses) 🌍

Virus images are not just pictures; they are glimpses into a **hidden world** that exists at the microscopic level! 🤯 Captured using advanced **electron microscopy**, these images reveal the intricate details of viruses—tiny, elusive entities that can have a huge impact on the world around us.

### Why Are Virus Images So Special? ✨
1. **Microscopic Marvels**: Virus images are captured using **Transmission Electron Microscopy (TEM)**, allowing us to zoom in to **nanometer scales** where viruses reside—so small that we can barely comprehend their size! 😲
   
2. **Shapes and Structures**: From **spherical** to **spiral-shaped** and more, viruses come in a stunning array of forms, each with its own story to tell. These shapes help us understand **how viruses interact** with the world, infecting cells and potentially causing diseases. 🌐🦠

3. **The Challenge of Clarity**: Capturing these microscopic creatures isn't easy! Due to their **minuscule size** and the limitations of imaging technology, virus images can often be **blurry** or **noisy**. But that's part of the excitement! It’s like looking for hidden treasure inside an image. 🔍💎

4. **Annotations Are the Key**: While the images might not provide **full segmentation masks** (perfect outlines of the virus), they come with **center points or centerlines** that guide us in identifying virus particles. These annotations are crucial for the next step: training AI to recognize and classify these viruses! 🤖

5. **The Power of Virus Images**: Beyond just being fascinating, these images help **scientists** and **doctors** unlock secrets about virus behavior, which is essential for **developing cures**, **treatments**, and **vaccines**. Every image could be a clue in the race to fight deadly diseases. 💪🧬

---


## 🦠 Dataset

The **Virus Dataset** consists of **16207 images** across **14 virus classes**, captured using two different electron microscopes. It contains both spherical and elongated virus particles, annotated by center points or centerlines.

### Virus Classes & Image Counts 📸:

| Virus Class       | Number of Images |
|-------------------|------------------|
| **Rotavirus**      | 950              |
| **Papilloma**      | 1504             |
| **Influenza**      | 1411             |
| **Adenovirus**     | 963              |
| **Lassa**          | 1165             |
| **Orf**            | 884              |
| **CCHF**           | 1067             |
| **Astrovirus**     | 1085             |
| **Cowpox**         | 956              |
| **Norovirus**      | 1091             |
| **Nipah virus**    | 902              |
| **Marburg**        | 1345             |
| **Rift Valley**    | 1519             |
| **Ebola**          | 1365             |

### Key Dataset Details 📸:
- **Total Images**: 16207 📊
- **Virus Classes**: 24 🦠
- **Annotation**: Center points or centerlines (no full segmentation masks) 😅
- **Challenges**: Noisy, blurry images, varying magnifications 🔍

---
## 🖼️ Visualization: A Window into the Invisible World  

### Why Visualization? 🌟  
Visualization transforms raw data into a story. It helps us explore the dataset, debug models, and interpret predictions. From **heatmaps** that reveal model attention to **class distributions** that highlight imbalances, visualization is the bridge between data and understanding.
| Folder                | Befor shuffling                                                                                      |  After shuffling  |
|----------------------|-------------------------------------------------------------------------------------------|--------------------------------|
| **Train**           | ![Normal Class](https://github.com/fatma2123456/Virus-Detection-Model/blob/main/images/data/Train.png)  |![Normal Class](https://github.com/fatma2123456/Virus-Detection-Model/blob/main/images/data/After%20Spliting%20Train.png) |
| **Test** | ![Pneumonia Class](https://github.com/fatma2123456/Virus-Detection-Model/blob/main/images/data/Test.png) |![Pneumonia Class](https://github.com/fatma2123456/Virus-Detection-Model/blob/main/images/data/Test%20Set.png) |
| **Validation**        | ![COVID-19 Class](https://github.com/fatma2123456/Virus-Detection-Model/blob/main/images/data/Validation.png)      | ![Pneumonia Class](https://github.com/fatma2123456/Virus-Detection-Model/blob/main/images/data/Validton%20Set.png)|
