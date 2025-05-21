# 🧠 Motor Imagery Classification using Deep Learning

Welcome to the Deep Learning-based Motor Imagery Classification repository!  
This project focuses on classifying EEG-based motor imagery signals using cutting-edge deep learning models tailored for brain-computer interface (BCI) applications.

---

## 🔍 What This Project Does

This repository implements and compares three powerful models for EEG motor imagery classification:

- ⚙️ **DeepConvNet** — Robust CNN-based model for spatial feature extraction.
- 🔄 **Temporal Convolutional Network (TCN)** — Effective for capturing temporal dynamics in EEG signals.
- 🧬 **Hybrid Model** — Combines DeepConvNet, TCN, and an Attention Mechanism for enhanced performance.

---

## 📁 Dataset Access

We use benchmark EEG datasets for training and evaluation:

- **BCI Competition IV Dataset 2a**: [Download here](https://www.bbci.de/competition/iv)

---

## ⚡ Why These Models?

Each model targets different aspects of EEG signal characteristics:

| Model          | Use Case                                      |
|----------------|-----------------------------------------------|
| DeepConvNet    | Strong spatial feature extraction             |
| TCN            | Temporal sequence modeling with stability     |
| Hybrid Model   | Best of spatial, temporal, and attention info |

---

## 🧠 How It Works

1. **Preprocessing**:
   - Bandpass filtering, ICA for artifact removal
   - Normalization and segmentation of EEG signals

2. **Model Architectures**:
   - **DeepConvNet**: Multiple convolution + pooling layers optimized for EEG.
   - **TCN**: Temporal convolutions with SELU activations for stability.
   - **Hybrid Model**: Fuses DeepConvNet and SNN-TCN outputs with an attention layer.

3. **Training**:
   - Cross-entropy loss, Adam optimizer
   - Subject-wise and cross-subject validation strategies



