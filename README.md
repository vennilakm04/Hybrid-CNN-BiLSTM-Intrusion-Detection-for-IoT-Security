# Hybrid CNN-BiLSTM Intrusion Detection for IoT Security

## Overview

This project presents a hybrid deep learning approach for IoT intrusion detection using the CICIoT2023 dataset. The model combines Convolutional Neural Networks (CNN) and Bidirectional Long Short-Term Memory (BiLSTM) to classify multiple network attack categories effectively.

## Objective

The aim is to improve intrusion detection accuracy in highly imbalanced IoT network traffic by extending a baseline CNN architecture with sequence learning capability.

## Dataset

* Dataset Used: CICIoT2023
* Type: IoT network traffic intrusion dataset
* Classes: Multiple attack and benign traffic categories

## Methodology

1. Data preprocessing and cleaning
2. Label encoding
3. Rare-class filtering
4. SMOTE balancing for class imbalance
5. CNN feature extraction
6. BiLSTM sequence learning
7. Softmax multiclass classification

## Model Architecture

* Conv1D
* MaxPooling1D
* Dropout
* Bidirectional LSTM
* Dense Output Layer

## Performance

* Test Accuracy: 98%
* Weighted F1-score: 0.97

## Novelty

The original CNN model from the reference study was improved by integrating a Bidirectional LSTM layer after convolutional feature extraction to capture sequential feature dependencies more effectively.

## Output Generated

* Confusion Matrix
* Classification Report
* Accuracy Curve
* Loss Curve

## Libraries Used

* Python
* TensorFlow
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

## Project Outcome

This model demonstrates strong performance for multiclass intrusion detection in IoT environments and can be extended for real-time cybersecurity applications.
