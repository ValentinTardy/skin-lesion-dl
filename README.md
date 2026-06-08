# Skin Lesion Classification — Deep Learning Project

## Section 12 — Final Project Report

**Authors:** Valentin Gabriel Paul TARDY (5999252044) | Ali MAHHA (5999252001)

**Submission date:** June 9, 2026

---

## Project Overview
Automated classification of skin lesions using Deep Learning on the HAM10000 dataset.
Comparative study between a Custom CNN and MobileNetV2 transfer learning.

## Dataset
- **HAM10000** — 10,015 dermatoscopic images, 7 classes
- Source: [Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

## Models
| Model | Accuracy | Macro F1 |
|-------|----------|----------|
| Logistic Regression (baseline) | 69.06% | 0.367 |
| MobileNetV2 (Transfer Learning) | 73.92% | 0.345 |
| **Custom CNN (Scratch)** | **79.97%** | **0.607** |

## How to run
Open `Skin_Lesion_Classification_Colab.ipynb` in Google Colab and follow the cells in order.

## Tech Stack
Python 3.12 | TensorFlow 2.x | Keras | Scikit-learn | Google Colab (T4 GPU)
