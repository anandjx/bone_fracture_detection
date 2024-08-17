# bone_fracture_detection
Detection of Fractures from X-ray Plates

Overview
This repository contains a Convolutional Neural Network (CNN) model for detecting fractures in X-ray images. The model is trained on the Fracture-Multi-Region-X-Ray-Data dataset from Kaggle, aiming to classify X-ray plates into two categories: fracture and no fracture.



Model Architecture
The model is built using a deep CNN architecture with the following layers:

Convolutional Layers:

5 Convolutional Layers with ReLU activation and Batch Normalization.
MaxPooling layers to reduce spatial dimensions.
Fully Connected Layers:

2 Fully Connected Layers with dropout for regularization.
Output layer for binary classification.

Training
Loss Function: Binary Cross Entropy with Logits (nn.BCEWithLogitsLoss)
Optimizer: Adam with learning rate of 0.0001
Epochs: 15 but also configurable in the training script


Performance Metrics
Accuracy: 96%
Precision: 0.97
Recall: 0.97
F1 Score: 0.97
These metrics indicate a highly effective model for identifying fractures in X-ray images.
