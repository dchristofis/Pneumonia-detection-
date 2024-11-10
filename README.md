# Pneumonia-detection-
This project leverages deep learning, specifically a Convolutional Neural Network (CNN), to classify chest X-ray images as either Pneumonia or Normal. The model is trained using the NIH Chest X-ray Dataset, and is built in Python using TensorFlow and Keras.

# **Project Overview
The goal of this project is to create a CNN model that can accurately classify chest X-ray images as either Pneumonia or Normal. Pneumonia, an infection that inflames air sacs in the lungs, can be detected from X-ray images, making this approach a potential tool for medical diagnosis.

# **Data Preprocessing
Images are resized to 128x128 pixels for model compatibility.
Data is split into Training, Validation, and Test sets.
Data Augmentation techniques, such as rotation and zoom, are applied to improve model generalization.

# **Model Architecture
The model is a Convolutional Neural Network (CNN) designed to handle 2D image data. It consists of:

Convolutional Layers: To capture spatial features from X-ray images.
MaxPooling Layers: To reduce spatial dimensions and control overfitting.
Fully Connected Layers: For classification based on learned features.
Dropout Layers: To prevent overfitting by randomly dropping units during training.
The model outputs a probability score, which is thresholded to classify each image as either Pneumonia or Normal.

# **Results
The model achieved the following metrics on the test set (predicting true pneumonia):

Accuracy: 97%
Precision: 98%
Recall: 98%
F1-Score: 98%