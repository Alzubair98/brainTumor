# Multi-Class Brain Tumor Classification

## 📄 Authors

**Alzubair Alqaraghuli**  
**Serkan Ozturk**

## 🧠 Project Overview

This repository contains the implementation for a research project on **multi-class brain tumor classification** using **ConvNeXt** architecture with **transfer learning** and **fine-tuning techniques**. The study focuses on classifying MRI brain scans into three tumor types: **glioma**, **meningioma**, and **pituitary tumor**, as well as the **normal** class.

By leveraging pre-trained ConvNeXt models (Tiny, Small, Base, and Large), we demonstrate the effectiveness of transfer learning in enhancing classification performance on medical imaging tasks, even with limited annotated data.

## 📊 Dataset

The dataset used in this project is publicly available and can be downloaded from the following Figshare link:

🔗 [Brain Tumor Dataset on Figshare](https://figshare.com/articles/dataset/brain_tumor_dataset/1512427)

The dataset contains T1-weighted contrast-enhanced MRI images categorized into:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor

## 🚀 Key Features

- Fine-tuning of multiple ConvNeXt variants
- Transfer learning applied to a medical imaging domain
- Data preprocessing and augmentation pipeline
- Multi-class classification of brain tumor types
- Evaluation using accuracy, precision, recall, F1-score, specificity, and sensitivity

## 📌 Requirements

- Python 3.8+
- PyTorch
- torchvision
- matplotlib
- scikit-learn
- OpenCV
- NumPy

---

## 🧪 Getting Started

The full implementation of this project is provided in the Jupyter Notebook file:

📘 `brain_tumor_multi_classification.ipynb`

To run the code:

1. Make sure you have Jupyter Notebook installed (you can install it via `pip install notebook` or using Anaconda).
2. Open the terminal and run:
3. Navigate to the file `brain_tumor_mutli_classification.ipynb` and open it in your browser.

---
