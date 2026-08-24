# Pipeline Defect Anomaly Detection

Reproducible implementation and experimental results for oil and gas pipeline defect
detection using anomaly detection under scarce labelled defect data.

This repository accompanies the dissertation *"Deep Learning-based Anomaly Detection
for Oil and Gas Pipeline Defect Detection and Integrity Management"* (KF7029, MSc
Advanced Computer Science, Northumbria University).

## Overview

This study compares three anomaly detection paradigms — reconstruction-based deep
learning, boundary-based deep learning, and classical statistical methods — across
two public pipeline datasets:

- **K-Pipelines** (image dataset, synthetically generated corrosion imagery)
- **US DOT Oil Pipeline Accidents** (tabular incident records)

A hybrid framework combining classical and deep learning anomaly scores is also
investigated.

## Environment and Dependencies

- Python 3.10
- PyTorch
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- Pillow
- opencv-python
- scipy

Install with:
