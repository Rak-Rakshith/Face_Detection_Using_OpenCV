# Real-Time Face Detection using OpenCV

This project implements real-time face detection using a webcam feed and the Haar Cascade classifier provided by OpenCV.

## Description

The application captures live video frames from the system camera and detects human faces using a pre-trained Haar Cascade model.  
Detected faces are highlighted with bounding boxes in real time.  
The program runs continuously until manually terminated by the user.

## Technologies Used

- Python
- OpenCV (cv2)
- Haar Cascade Classifier

## Working Principle

- Accesses the system webcam using OpenCV
- Converts video frames to grayscale
- Applies Haar Cascade classification for face detection
- Draws rectangles around detected faces
- Displays the processed video feed in real time

## Requirements

- Python 3.x
- OpenCV library
- Functional webcam

## How to Run

1. Install OpenCV
   ```bash
   pip install opencv-python
2. Ensure the Haar cascade XML file path is correctly set
3. Run the Python script
4. Press q to exit the video stream

## Key Features

- Real-time face detection
- Lightweight and fast execution
- Uses pre-trained classical computer vision model

## Limitations

- Performance depends on lighting conditions
- Haar cascades are less accurate compared to deep learning models

## Future Improvements

- Replace Haar Cascade with deep learning-based face detectors
- Improve detection accuracy in low-light conditions
- Add face recognition functionality

## Author

Rakshith S
