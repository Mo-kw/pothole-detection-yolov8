# Pothole Detection Using YOLOv8

This repository contains a Colab notebook and supporting scripts for detecting potholes in images using the YOLOv8 object detection model by Ultralytics.

## Project Overview
The goal is to build a robust pothole detection system by:
- Downloading and preprocessing a pothole dataset.
- Converting annotations from COCO format to YOLO format.
- Training a YOLOv8 model on the dataset.
- Visualizing bounding boxes on sample images.
- Running inference on test images and visualizing results.

## Features
- Dataset preparation and cleanup scripts.
- Conversion from COCO to YOLO annotation format.
- Custom dataset YAML creation for training.
- Training YOLOv8 with pretrained weights.
- Prediction and visualization of pothole detections.

## How to Use
1. Clone this repo or open the notebook directly in Google Colab.
2. Run cells sequentially to download data, preprocess, train, and test the model.
3. Adjust parameters such as epochs, batch size, or confidence threshold as needed.
4. Visualize results directly in the notebook.

## Dependencies
- Python 3.x
- Ultralytics YOLO (`pip install ultralytics`)
- OpenCV
- Matplotlib
- Other standard Python libraries (json, yaml, etc.)

## Dataset
The dataset is sourced from [Roboflow](https://universe.roboflow.com/), containing annotated pothole images.

## License
Specify your license here (e.g., MIT License)

---

Feel free to contribute or raise issues!

