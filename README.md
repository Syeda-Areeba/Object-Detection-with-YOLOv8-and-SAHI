# Object Detection with YOLOv8 and SAHI

## Overview

This project uses YOLOv8 for object detection, leveraging Roboflow for dataset management and SAHI for improved predictions on larger images or videos.

## Installation

Install the required packages using:

- `ultralytics==8.0.196`
- `roboflow`
- `ultralytics sahi`

## Setup

1. **Roboflow Integration**: 
   - Connect to your Roboflow account and download the dataset for training and validation.

2. **Model Training**: 
   - Use a pre-trained YOLOv8 model for training with your dataset.

3. **Validation**: 
   - Evaluate the model performance using metrics like mean Average Precision (mAP).

## Inference

1. **Image Prediction**:
   - Perform object detection on images with the trained model and visualize results.

2. **Advanced Inference with SAHI**:
   - Use SAHI for slicing and predicting on large images or videos to enhance detection performance.

## Results Visualization

- View prediction results and ground truth images side-by-side to assess model performance.
- Export and visualize predictions using SAHI for improved accuracy on large or complex images.

## Notes

- Ensure you replace placeholder values such as API keys and file paths with actual values relevant to your setup.
