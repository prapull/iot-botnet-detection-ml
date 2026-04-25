# IoT-Guard: Two-Stage Hierarchical Ensemble for IoT Botnet Detection

## Overview
IoT-Guard is a research project proposing a hierarchical ML framework for detecting 
and classifying IoT botnet attacks with cross-device generalization.

## System Architecture
**Stage 1: Binary Detection**
- XGBoost classifier separates benign from attack traffic
- Evaluated under 9-fold Leave-One-Device-Out (LODO) protocol

**Stage 2: Fine-Grained Classification**  
- 1D-CNN processes attack-confirmed traffic
- Classifies into Mirai/Gafgyt attack subtypes

## Results
- 99.99% accuracy on N-BaIoT dataset (9 IoT devices)
- Cross-device generalization via LODO evaluation protocol

## Dataset
N-BaIoT — network traffic from 9 real IoT devices infected with Mirai and Gafgyt botnets.

## Status
Research paper submitted for publication. Code withheld pending review.

## Technologies
Python, XGBoost, TensorFlow/Keras, Scikit-learn
