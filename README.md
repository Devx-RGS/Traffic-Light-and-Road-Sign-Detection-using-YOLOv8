# Traffic Light and Road Sign Detection using YOLOv8

## Overview
This project implements an image-based object detection system using YOLOv8 to detect traffic lights and road signs.  
The model is trained on a custom dataset and evaluated using standard object detection metrics to assess detection accuracy.

## Technologies Used
- Python
- YOLOv8 (Ultralytics)
- Google Colab

## Dataset
- Custom annotated dataset consisting of traffic scene images
- Classes include:
  - Stop Sign
  - Speed Limit Signs
  - Red Traffic Light
  - Green Traffic Light

## Methodology
- YOLOv8 was used as the core object detection model.
- The model was trained on labeled images using supervised learning.
- Training performance was monitored using loss values and detection metrics.
- Image-based inference was performed to validate model predictions.

## Results
- mAP@50 ≈ 0.92
- mAP@50–95 ≈ 0.79
- The model demonstrates strong performance in detecting traffic signs and traffic lights from images.
