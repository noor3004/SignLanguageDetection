# Sign Language Detection

This repository contains an implementation of a Sign Language Detection system using keypoint classification. The model processes keypoint data from hand landmarks to classify different sign language gestures.

## Features
- Uses TensorFlow Lite for efficient model inference.
- Classifies hand keypoints into different sign language gestures.
- Includes a trained model (`keypoint_classifier.tflite`).
- Implements keypoint classification using a neural network.

## Repository Structure
```
.
├── app.py                         # Main application script
├── keypoint.csv                    # Dataset containing keypoint data
├── keypoint_classification.ipynb    # Jupyter notebook for model training
├── keypoint_classifier.hdf5         # Trained model in HDF5 format
├── keypoint_classifier.hdf5.keras   # Alternative trained model format
├── keypoint_classifier.py           # Python script for keypoint classification
├── keypoint_classifier.tflite       # TensorFlow Lite model
├── keypoint_classifier_label.csv    # Labels for the classifier
├── point_history_classification.ipynb # Notebook for point history classification
```

## Installation
To run this project, install the required dependencies:
```sh
pip install numpy tensorflow
```

## Usage
Run the main application:
```sh
python app.py
```

## Model Details
The classifier is implemented in `keypoint_classifier.py` and uses TensorFlow Lite for efficient inference. The model processes hand landmarks and predicts the corresponding sign language gesture.
## Outputs
![yes](https://github.com/user-attachments/assets/9f5a2397-69d0-4e41-bd56-89f36b227bfd)
![iloveyou](https://github.com/user-attachments/assets/d68f1bc3-45e9-4506-8de4-96883a748842)
![thanks](https://github.com/user-attachments/assets/9faf35bc-a0af-4fa1-9f9d-e68faa320610)
![hello](https://github.com/user-attachments/assets/0eb11c52-1878-46ec-b5f8-e209e7c3c3b9)

https://drive.google.com/file/d/10WRrfGqRB33IcIwsdnMFZqTjlGqVxYu9/view?usp=drive_link


