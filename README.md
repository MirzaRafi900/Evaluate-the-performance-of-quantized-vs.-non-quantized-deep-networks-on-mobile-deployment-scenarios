# Evaluate the Performance of Quantized vs. Non-Quantized Deep Networks on Mobile Deployment Scenarios

## Overview

This repository contains coursework for the Deep Learning subject (MDSA 7113).

The project investigates the performance differences between quantized and non-quantized deep neural network models in mobile deployment scenarios. The study focuses on evaluating the trade-offs between model accuracy, inference speed (latency), and model size when deploying deep learning models on resource-constrained devices.

## Objective

The main objectives of this project are:

- Implement a convolutional neural network (CNN) model.
- Apply model quantization techniques.
- Compare quantized and non-quantized models.
- Evaluate performance using:
  - Accuracy
  - Inference Speed (Latency)
  - Model Size
- Analyze the suitability of quantized models for mobile and edge AI applications.

## Dataset

Dataset: CIFAR-10

The CIFAR-10 dataset contains 60,000 color images across 10 object categories and is commonly used for image classification research.

## Model Architecture

Model: MobileNetV2

MobileNetV2 was selected because it is a lightweight convolutional neural network architecture designed for mobile and embedded devices.

## Quantization Method

Post-Training Quantization (PTQ) will be applied to reduce model size and improve deployment efficiency while maintaining acceptable prediction accuracy.

## Evaluation Metrics

The following performance metrics will be compared:

- Classification Accuracy
- Inference Latency
- Model Size
- Deployment Efficiency

## Tools and Frameworks

- Python
- TensorFlow
- TensorFlow Lite
- Jupyter Notebook
- NumPy
- Matplotlib

## Repository Structure

```text
├── notebooks/
├── dataset/
├── models/
├── results/
├── report/
└── README.md
