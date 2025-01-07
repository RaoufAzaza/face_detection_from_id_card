# face_detection_from_id_card
# Face Detection and Cropping Tool

This repository provides a Python script for detecting, cropping, and saving faces from images using the **MTCNN** (Multi-task Cascaded Convolutional Networks) library.

## Features

- **Face Detection**: Detects faces in an input image using MTCNN.
- **Face Cropping and Resizing**: Crops detected faces, enlarges the bounding box, and resizes faces to a fixed dimension of 150x150 pixels.
- **Face Saving**: Saves cropped and resized faces to a directory (`/content/clients`) with unique filenames.
- **Model Saving**: Saves the trained MTCNN model in `.pkl` format for reuse.
