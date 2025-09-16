# Biomedical Image Segmentation Using U-Net in PyTorch

This project presents a clean and modular implementation of the U-Net architecture for **binary biomedical image segmentation** using PyTorch. 

---

## 🚀 Overview

- **Architecture**: U-Net (custom PyTorch implementation)
- **Task**: Semantic segmentation (binary — foreground vs background)
- **Framework**: PyTorch (with NumPy, Matplotlib, scikit-learn)
- **Evaluation**: Pixel-level classification report and accuracy
- **Project Format**: Jupyter Notebook (`.ipynb`)

---

## 🔍 Project Features

- 🧠 End-to-end pipeline: data preprocessing, model definition, inference, and evaluation
- 🔄 Preprocessing includes center cropping and normalization
- 📊 Pixel-wise evaluation using `classification_report` and `accuracy_score`
- 🧪 Binary segmentation with sigmoid activation and thresholding
- 📈 Visual comparison of input images and masks (matplotlib)
- 🔧 Easily extensible to add Dice, IoU, or multi-class support

---

## 🧬 Dataset Overview

The dataset used in this project is derived from the **2012 ISBI Challenge** on segmentation of neuronal structures in electron microscopic stacks.

- **Modality**: Serial section Transmission Electron Microscopy (ssTEM)  
- **Organism**: *Drosophila* first instar larva ventral nerve cord (VNC)  
- **Resolution**: ~4x4x50 nm/pixel  
- **Volume size**: Approximately 2 × 2 × 1.5 microns  
- **Training Set**: 30 image slices and corresponding binary labels  
- **Label Format**: Binary masks with white pixels marking segmented structures (e.g., membranes) and black pixels as background

> This dataset is specifically structured for evaluating biomedical segmentation algorithms on high-resolution neuronal imagery.

---

## 📚 Reference

- Ronneberger, Olaf, Philipp Fischer, and Thomas Brox.  
  *"U-Net: Convolutional Networks for Biomedical Image Segmentation."*  
  MICCAI, 2015.

- ISBI 2012 EM Segmentation Challenge:  
  [https://brainiac2.mit.edu/isbi_challenge/](https://brainiac2.mit.edu/isbi_challenge/)

