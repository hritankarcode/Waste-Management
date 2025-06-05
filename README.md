# Object Detection with TensorFlow and COCO Annotations

This repository contains a Python script for performing object detection using a pre-trained TensorFlow model with COCO-format annotations. The script demonstrates how to:
- Load a trained model
- Process images
- Draw ground truth bounding boxes from COCO annotations
- Display the results

- ## Features

- **Model Loading**: Loads a pre-trained TensorFlow/Keras model 
- **COCO Annotation Handling**: Parses JSON annotations in COCO format
- **Image Preprocessing**: Resizes and normalizes images for model input
- **Bounding Box Visualization**: Draws ground truth bounding boxes with class labels

## Detection Results

### Original Image (Input)
![Original Image](Screenshot2.png)  
*Raw input image before processing - shows the scene without any annotations*

### Detected Objects (Output)
![Detected Image](Screenshot1.png)  
