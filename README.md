# Face Detection

## Overview

This project is a face detection application built using Python and OpenCV. It processes a pre-recorded video and detects human faces in each frame.

When a face is detected, the system draws a bounding box around it and displays the label "Face".

The project uses the Haar Cascade Classifier provided by OpenCV for face detection.

## Features

- Detects human faces in video frames.
- Draws a bounding box around detected faces.
- Displays the label "Face" above each detected face.
- Processes a pre-recorded video without requiring a live camera.
- Simple and easy to run using Anaconda and Visual Studio Code.

## Technologies Used

- Python
- OpenCV
- Haar Cascade Classifier
- Anaconda
- Visual Studio Code (VS Code)

## Project Files

Face_Detection/
- main.py
- video.mp4
- haarcascade_frontalface_default.xml
- result.png
- README.md

## How to Run

### 1. Create the Anaconda Environment

conda create -n face_recognition python=3.10

### 2. Activate the Environment

conda activate face_recognition

### 3. Install OpenCV

pip install opencv-contrib-python

### 4. Run the Project

Open the project folder in Visual Studio Code and run:

python main.py

The program will open the video and detect human faces. A bounding box and the label "Face" will appear around each detected face.

Press Q to close the video.

## How It Works

1. The program loads the Haar Cascade face detection model.
2. It opens the input video using OpenCV.
3. Each video frame is converted to grayscale.
4. The Haar Cascade classifier searches for human faces.
5. A bounding box is drawn around each detected face.
6. The label "Face" is displayed above the detected face.
7. The processed video is displayed on the screen.

## Prediction Example

The image below shows an example of the project output.

Face Detection Result

The system successfully detects a human face and highlights it with a bounding box.

## Result

The project successfully demonstrates face detection from a pre-recorded video using OpenCV and the Haar Cascade Classifier.

## Author

Wesal Ibrahim Alsharif

CS Student at Taif University
