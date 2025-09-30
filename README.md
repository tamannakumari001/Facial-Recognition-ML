# Facial Recognition Using Machine Learning

This project implements a facial recognition system using TensorFlow/Keras. It collects images from a webcam, uses the LFW (Labeled Faces in the Wild) dataset as negative examples, and trains a model to recognize faces.

---

## Features

- Downloads and uses the LFW dataset for negative samples.
- Captures webcam images for anchors and positive samples.
- Organizes images into folders:
  - `data/anchors` – anchor images
  - `data/positive` – positive images
  - `data/negatives` – negative images (LFW dataset)
- Uses TensorFlow/Keras for model training.
- Saves the trained model in `.keras` or `.h5` format.
- Supports loading the saved model for inference.

---

## Requirements

- Python 3.10+  
- TensorFlow 2.x  
- OpenCV (`cv2`)  
- NumPy  
- PIL (Pillow)  
- Scikit-learn  

Install required packages:

```bash
pip install tensorflow opencv-python-headless numpy pillow scikit-learn

