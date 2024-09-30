# Automatic Plate Number Recognition (APNR) Project - Object Detection and Oriented Bounding Box (OBB) 

## Overview
This project implements two different tasks: object detection using YOLOv8 and oriented bounding box (OBB) detection. The repository includes code for training, inference, and evaluation of models, as well as pre-trained weights.

## Folder Structure
### Explanation of Structure
- **runs/**: Contains the results of training, including model weights for both YOLOv8 and OBB.
  - **detect/**: Directory for YOLOv8 detection models.
    - **train9/**: Folder with training results for the YOLOv8 model.
      - **weights/**: Stores trained weights of the YOLOv8 model.
  - **obb/**: Directory for OBB detection models.
    - **train/**: Folder with training results for the OBB model.
      - **weights/**: Stores trained weights of the OBB model.
- **index_obb.ipynb**: Jupyter Notebook for working with the oriented bounding box detection model.
- **index.ipynb**: Jupyter Notebook for working with the YOLOv8 object detection model.
- **requirements.txt**: Lists the Python dependencies required to run the notebooks.

## Installation
To set up the environment, install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage
- **Object Detection (YOLOv8)**: Open `index.ipynb` to run inference on images using the YOLOv8 model.
- **Oriented Bounding Box Detection**: Open `index_obb.ipynb` to work with the OBB detection model.

## Results
Trained models can be found in the `runs` directory. You can evaluate the performance of the models by running the respective notebooks.

### Object Detection (YOLOv8)
- **Fitness**: 0.82
- **Precision**: 0.99
- **Recall**: 0.99
- **mAP50**: 0.99
- **mAP50-95**: 0.80
- **Inference Speed**: 2.91 seconds per image
- **Loss**: 0.0024

#### Test Set
- **Accuracy**: 0.97
- **Precision**: 1.00
- **Recall**: 0.97
- **F1-Score**: 0.98

### Oriented Bounding Box Detection (OBB)
- **Fitness**: 0.88
- **Precision**: 0.99
- **Recall**: 0.99
- **mAP50**: 0.99
- **mAP50-95**: 0.87
- **Inference Speed**: 3.82 milliseconds per image
- **Loss**: 0.0

#### Test Set
- **Accuracy**: 0.94
- **Precision**: 1.00
- **Recall**: 0.94
- **F1-Score**: 0.97

