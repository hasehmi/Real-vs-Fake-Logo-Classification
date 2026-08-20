# Real vs. Fake Logo Classification using CNN

## Project Description
This project implements a Convolutional Neural Network (CNN) to detect and classify logos as either "Real" or "Fake". It features a custom data generation script that creates a synthetic dataset of logos using OpenCV, applying random noise and Gaussian blur to simulate fake variations. Built with TensorFlow and Keras, the deep learning model efficiently learns spatial hierarchies to distinguish between authentic and manipulated images.

## Key Features & Achievements
* **Synthetic Dataset Generation:** Automated the creation of a balanced dataset containing 400 images (200 real, 200 fake) using OpenCV shape drawing, text rendering, and noise injection techniques.
* **CNN Architecture:** Built a custom deep learning model using TensorFlow and Keras, featuring multiple `Conv2D` and `MaxPooling2D` layers, followed by `Dense` and `Dropout` (0.5) layers to prevent overfitting.
* **High-Accuracy Training:** Trained the Sequential model over 10 epochs with a batch size of 16, achieving a perfect 100% test accuracy on the validation split.
* **Performance Evaluation:** Utilized `scikit-learn` to generate comprehensive confusion matrices and classification reports to rigorously validate model precision, recall, and f1-scores.
* **Visual Prediction:** Integrated Matplotlib to visually display individual test images alongside their predicted labels for quick and clear verification.
