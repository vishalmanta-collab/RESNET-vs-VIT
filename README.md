# Beyond Accuracy: A Comprehensive Evaluation of ResNet50 and Vision Transformer (ViT-B16) for Trustworthy Pneumonia Detection from Chest X-Ray Images

## Overview

This repository contains the implementation accompanying the research paper:

**"Beyond Accuracy: A Comprehensive Evaluation of ResNet50 and Vision Transformer (ViT-B16) for Trustworthy Pneumonia Detection from Chest X-Ray Images."**

The study presents a fair comparison between a convolutional neural network (ResNet50) and a transformer-based architecture (ViT-B16) for automated pneumonia detection using chest X-ray images. Unlike conventional studies that primarily report classification accuracy, this work evaluates the models from multiple perspectives, including robustness, calibration, computational efficiency, explainability, and statistical significance.

---

## Features

* Binary pneumonia classification using chest X-ray images
* Transfer learning with ResNet50 and Vision Transformer (ViT-B16)
* Identical preprocessing, training, and evaluation settings for fair comparison
* Classification evaluation

  * Accuracy
  * Precision
  * Recall
  * Specificity
  * F1-score
  * Balanced Accuracy
  * ROC-AUC
* Calibration analysis

  * Expected Calibration Error (ECE)
  * Brier Score
  * Reliability Diagrams
* Robustness evaluation

  * Gaussian Noise
  * Gaussian Blur
  * Brightness Variation
  * Accuracy Drop Analysis
* Computational analysis

  * Parameter Count
  * FLOPs
  * Inference Time
* Statistical analysis

  * McNemar's Test
  * 95% Confidence Intervals
* Explainability

  * Grad-CAM Visualizations
* Qualitative error analysis

---

## Dataset

Experiments were performed using the **RSNA Pneumonia Detection Challenge** dataset.

Dataset:
https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge

Please download the dataset directly from Kaggle and organize it according to the directory structure described below.

---





## Reproducibility

Both ResNet50 and ViT-B16 were trained under identical experimental conditions:

* Image size: 224 × 224
* Batch size: 32
* Epochs: 10
* ResNet50 Optimizer: Adam
* ViT-B16 Optimizer: AdamW
* Learning rate: 1e-4
* Cross-entropy loss
* ImageNet pretrained weights

---

## Results

The repository includes scripts for reproducing:

* Model training
* Performance evaluation
* ROC curves
* Confusion matrices
* Calibration analysis
* Robustness experiments
* McNemar statistical test
* Computational complexity analysis
* Grad-CAM visualizations

---



## License

This repository is intended for academic and research purposes.

---

## Contact

For questions regarding the implementation, please contact the corresponding author.
