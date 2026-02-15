# Hybrid CNN–LSTM–Attention Model for Network Intrusion Detection

## Overview

This repository contains the research paper and implementation for a **hybrid deep learning–based Intrusion Detection System (IDS)** that combines **CNN, LSTM, and Attention mechanisms** for multi-class network attack detection.

The model is designed to improve intrusion detection performance by capturing:

* Local feature patterns using CNN
* Temporal dependencies using LSTM
* Important sequence information using Attention

The system was evaluated on the **CICIDS2017 dataset** and achieved **97.07% accuracy** in detecting multiple types of network attacks.

---

## Research Paper

**Title:** Hybrid Deep Learning Architecture for Network Intrusion Detection: A CNN–LSTM–Attention Approach

This research focuses on:

* Designing a hybrid deep learning IDS architecture
* Feature selection using Mutual Information
* Handling class imbalance using SMOTE and undersampling
* Multi-class intrusion detection
* Ablation study to evaluate contribution of each component

---

## Dataset

**Dataset Used:** CICIDS2017

Attack Classes:

* Benign
* DoS / DDoS
* PortScan
* Brute Force
* Web Attack
* Botnet ARES

Dataset contains:

* 2.8 million network flows
* 79 features (reduced to top 50 using feature selection)

---

## Model Architecture

Hybrid Model Components:

```
Input Features
     ↓
CNN Layers (Feature Extraction)
     ↓
LSTM Layers (Temporal Learning)
     ↓
Attention Layer (Feature Importance)
     ↓
Dense Layer
     ↓
Softmax Output
```

---

## Performance

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 97.07% |
| Precision | 98.24% |
| F1 Score  | 97.50% |

---

## Key Contributions

* Hybrid CNN–LSTM–Attention IDS model
* Feature selection using Mutual Information
* Class balancing using SMOTE
* Multi-class attack detection
* Ablation study for architecture analysis

---

## Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* Deep Learning
* Cybersecurity / Intrusion Detection

---

## Repository Contents

```
Research_Paper.pdf
README.md
```


---

## Skills Demonstrated

* Deep Learning
* Cybersecurity
* Intrusion Detection Systems
* Neural Networks
* CNN
* LSTM
* Attention Mechanisms
* Research and Technical Writing

---

## Authors

Maryam Amjad
BS Data Science

Maryam Khalid
BS Data Science
National University of Computer and Emerging Sciences
