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

## License
This project is open-source and available under the MIT License.

