# IoT Botnet Detection using Machine Learning

## Overview
This project demonstrates a hybrid machine learning pipeline for detecting botnet activity in IoT network traffic.
The system is designed to first filter suspicious traffic using anomaly detection and then classify malicious traffic
using ensemble-based machine learning models.

The goal of this repository is to explain the **architecture, workflow, and inference logic** of the system in a clear
and practical way.

---

## System Architecture
The detection pipeline consists of two stages:

**Stage 1: Anomaly Detection**
- Identifies suspicious network traffic using unsupervised learning.
- Helps reduce unnecessary computation by filtering benign traffic early.

**Stage 2: Attack Classification**
- Applies ensemble-based classification only on flagged traffic.
- Improves robustness on imbalanced IoT security data.

---

## Key Concepts Used
- Unsupervised anomaly detection
- Feature compression / representation learning
- Ensemble machine learning models
- Handling imbalanced classification problems
- Pipeline-based ML system design

---

## Dataset
This project is based on the **N-BaIoT dataset**, which contains network traffic data from IoT devices under normal
and botnet attack conditions.

> The dataset is publicly available and is **not included** in this repository.

---

## Note on Training
Model training was performed offline due to high computational cost and large dataset size.
This repository focuses on demonstrating the **inference flow and system design**, rather than full model training.

---

## Repository Purpose
This repository is intended for:
- Learning and demonstration
- Understanding hybrid ML pipelines

It is **not intended** to be a one-click reproduction of research experiments.

---

## Technologies Used
- Python
- Scikit-learn
- TensorFlow / Keras
- Ensemble Machine Learning Models

