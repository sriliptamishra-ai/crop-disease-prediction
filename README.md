# crop-disease-prediction

## Overview

This project is an AI-based system that detects diseases in crop leaves using image processing and deep learning techniques. Farmers or users can upload an image of a plant leaf, and the system will predict the disease and suggest possible treatments.

It helps in early detection, reducing crop loss and improving agricultural productivity.

## Objective

The main objectives of this project are:

Identify diseases in crops using leaf images
Provide fast and accurate predictions
Assist farmers in taking timely action
Reduce dependency on manual inspection

## Working Principle
1. Image Input

User uploads or captures an image of a plant leaf.

2. Preprocessing
Resize image
Normalize pixel values
Remove noise (if needed)
3. Feature Extraction
In traditional ML → color, texture, shape
In deep learning → automatic feature extraction using CNN
4. Model Prediction
The trained model classifies the image into:
Healthy leaf
Diseased leaf (specific disease)
5. Output
Displays disease name
   (can add) Shows remedies or precautions
 Technologies Used
--> Programming Language
Python

## Libraries
NumPy → numerical operations
Pandas → data handling
Matplotlib → visualization
OpenCV → image processing
TensorFlow / Keras → deep learning

## Dataset
Images of plant leaves (healthy + diseased)
Common datasets:
PlantVillage dataset
Contains multiple crops like:
Tomato 
Potato 
Corn 

## Model Training
Data split into:
Training set
Validation set
Test set
Model used:
Convolutional Neural Network (CNN)
Steps:
Build CNN model
Compile using optimizer (Adam)
Train model using training data
Validate accuracy

## Model Testing
Test the model on unseen images
Evaluate performance using:
Accuracy
Loss
Confusion matrix

## Workflow
User uploads leaf image
Image is preprocessed
Model analyzes features
Disease is predicted
Result displayed to user

## Features
 Fast and automatic disease detection
 High accuracy using deep learning
 Easy to use interface
 Reduces manual effort
 Can be deployed on web/mobile
 
## Applications
Smart agriculture
Farmer assistance systems
Crop monitoring
Agricultural research

## Limitations
Accuracy depends on image quality
Requires large dataset for better performance
May not detect unseen diseases
Needs retraining for new crops

## Future Enhancements
 Mobile app integration
 Real-time detection using camera
 Weather-based disease prediction
 Advanced AI models (Transfer Learning)
 Voice-based output for farmers
 Viva Explanation (Short & Strong)
 
## my overview
“This project uses deep learning to detect crop diseases from leaf images. A CNN model is trained on a dataset of healthy and diseased leaves, and it predicts the disease when a new image is provided, helping farmers take early action.”

## Author
Srilipta mishra

