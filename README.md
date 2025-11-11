# Sign Language MNIST CNN Classifier with Real-Time Recognition

#Project Overview:
This project implements a Convolutional Neural Network (CNN) to classify American Sign Language (ASL) alphabets using the Sign Language MNIST dataset. The trained model is integrated with OpenCV and MediaPipe for real-time hand gesture recognition using a webcam, converting sign language inputs to readable text.

#Features:
Classifies 24 static ASL alphabets (A-Y excluding J and Z).

Preprocessing of image data from CSV format with normalization and reshaping.

CNN architecture optimized for gesture image classification.

Real-time sign detection and classification using OpenCV and MediaPipe Hands for accurate hand region segmentation.

On-screen display of predicted alphabets from live webcam feed.

Dataset
The Sign Language MNIST dataset contains 28x28 grayscale images representing hand signs for the ASL alphabets.

It provides separate train and test CSV files with corresponding labels.
