# Simple CNN Image Classifier (CIFAR-10)

A basic Convolutional Neural Network (CNN) implemented in TensorFlow/Keras to classify images from the CIFAR-10 dataset.

## Features
- Trains a 3-layer CNN on CIFAR-10 (60,000 images across 10 classes)
- Evaluates model performance on test data
- Supports custom image uploads for predictions
- Includes visualization of training progress and sample predictions

## Classes Predicted
The model classifies images into these 10 categories:
- Airplane ✈️
- Automobile 🚗
- Bird 🐦
- Cat 🐱
- Deer 🦌
- Dog 🐶
- Frog 🐸
- Horse 🐴
- Ship ⛴️
- Truck 🚚

## Requirements
- Google Colab (or Python 3.7+)
- TensorFlow 2.x
- Matplotlib
- NumPy

## How to Use
1. Open in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)
2. Run all cells sequentially
3. To test custom images:
   - Run the last cell
   - Upload an image when prompted
   - View the prediction result

## Expected Performance
- ~70% test accuracy after 10 epochs
- Training time: ~2 minutes on Colab GPU

## Customization
To modify:
- Change `epochs` in `model.fit()`
- Adjust CNN architecture in `model.Sequential()`
- Replace dataset by modifying `datasets.cifar10.load_data()`
