# Flower Species Classifier 🌸
This project is an image classification system that identifies the species of a flower from a photograph using a deep learning model built with Keras and TensorFlow. The model is trained to recognize five types of flowers: roses, daisy, dandelion, sunflowers, and tulips.

## Features
Image Upload and Prediction: Upload an image and get an instant prediction of the flower’s species.

Pre-trained Deep Learning Model: Uses a convolutional neural network (CNN) built and trained using TensorFlow/Keras.

Preprocessing: Images are resized and normalized with OpenCV and NumPy for robust prediction.

User-Friendly: Simple command-line interface for selecting images and viewing predictions.

Custom Label Mapping: Returns predictions as human-readable flower names.

## How It Works
Load and Preprocess Image: The selected image is read, resized to 180x180 pixels, converted to a normalized NumPy array, and prepared for the model.

Model Prediction: The processed image is fed into the trained model to get probability scores.

Class Determination: The output label is mapped to the corresponding flower name using a dictionary.
