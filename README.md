# 🦷 Oral Disease Classification using EfficientNet

This project focuses on detecting and classifying oral diseases from medical images using deep learning. After experimenting with multiple models including **EfficientNet** provided the best performance in terms of accuracy and generalization.

## 📂 Dataset

* **Source:** [Kaggle - Oral Diseases](https://www.kaggle.com/datasets/salmansajid05/oral-diseases)
* **Description:** Labeled image dataset for six types of oral diseases.
* **Classes:**

  * Calculus
  * Caries
  * Gingivitis
  * Ulcers
  * Tooth Discoloration
  * Hypodontia

## 🧪 Project Overview

This notebook (`oral_detection_efficientnet_improveedV1.ipynb`) includes:

* Mounting Google Drive for data access
* Splitting the dataset into `train`, `val`, and `test` folders (72/18/10)
* Visualizing 3 random images per class
* Plotting class distribution using a stacked bar chart
* Preparing the data for model training

## ✅ Model Comparison

| Model              | Accuracy |
| ------------------ | -------- |
| ResNet18           | 72%      |
| Vision Transformer | 78%      |
| **EfficientNet**   | **Best** |

✅ **EfficientNet was selected for final implementation due to its superior performance.**

## 🛠️ Requirements

* Python 3.x
* PyTorch
* torchvision
* scikit-learn
* matplotlib
* seaborn
* Pillow

Install with:

```bash
pip install torch torchvision scikit-learn matplotlib seaborn pillow
```

## 📊 Outputs

* Sample images per class
* Class distribution bar chart

## 📘 File

* `oral_detection_efficientnet_improveedV1.ipynb`: Main notebook with preprocessing and visualization.

---

