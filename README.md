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

* Test Accuracy: 97%
* Weighted F1-score: 0.97

## Novelty

The baseline CNN intrusion detection model was enhanced by adding a Bidirectional LSTM layer for sequential feature learning, along with SMOTE balancing and rare-class filtering to improve performance on imbalanced IoT traffic classes.


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

The final hybrid CNN-BiLSTM model achieved 97% multiclass classification accuracy on the CICIoT2023 dataset, with strong weighted F1-score performance and improved detection across dominant intrusion categories.


