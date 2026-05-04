# Face_Recogniser
A Python-based facial recognition system using OpenCV and the LBPH (Local Binary Patterns Histograms) algorithm. Features real-time face detection via Haar Cascades, automated dataset collection, and custom model training for individual identification. 

# Project Overview
This repository contains a facial recognition system implemented using Python and OpenCV. It uses a three-stage pipeline to identify individuals in real-time.

# Technical Stack
Algorithm: Local Binary Patterns Histograms (LBPH) for face recognition.

Detection: Haar Cascade Classifiers for real-time face localization.

Libraries: cv2 (OpenCV), numpy, and Pillow (PIL).

# Repository Structure
face_recogniser.ipynb: The main notebook containing dataset generation, model training, and recognition logic.

haarcascade_frontalface_default.xml: Pre-trained Haar Cascade model for face detection.

data/: Directory where captured face samples are stored (local only).

# How to Use
Generate Dataset: Run the first module to capture 200 grayscale samples via webcam.

Train Classifier: Run the second module to train the LBPH recognizer and save it as classifier.xml.

Real-time Recognition: Run the final module to start identifying faces with confidence scores.
