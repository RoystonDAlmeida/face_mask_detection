# Face Mask Detection

This project uses Computer Vision to detect face masks in images.

## Overview

This project implements a face mask detection system using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. It leverages the OpenCV library for real-time detection.

## Dataset

The project uses the "Face Mask Dataset" available on Kaggle. The dataset contains images of people with and without face masks.

## Requirements

- Python 3.x
- TensorFlow 2.x
- OpenCV
- NumPy
- Kaggle API

## Installation

1. Install the required libraries:

```bash
pip install tensorflow opencv-python numpy kaggle
```

2. Download the Kaggle API credentials and place them in your Google Colab environment.
   - This is done in the notebook using the Google Drive mount and Kaggle API setup.

## Usage

1. **Dataset Acquisition:** The notebook downloads the dataset from Kaggle using the API.
2. **Preprocessing:** The dataset is preprocessed to resize images and normalize pixel values.
3. **Model Building:** A CNN model is built using TensorFlow/Keras.
4. **Training:** The model is trained on the dataset.
5. **Detection:** Real-time detection is implemented using OpenCV.
6. **Inference:** The trained model is used to predict the presence of face masks in images.

## Steps to Run

1. Open the notebook in Google Colab.
2. Execute the cells in order.
3. Upload your test images to the Colab environment.
4. Run the inference cell to detect face masks.

## Results

The model achieves high accuracy in detecting face masks. Results are displayed as images with bounding boxes and labels indicating the presence or absence of a mask.

## Notes

- The project can be extended to implement real-time detection using a webcam or video feed.
