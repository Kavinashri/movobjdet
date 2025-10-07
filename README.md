#  Moving Object Detection using OpenCV

This project demonstrates a simple Python script for detecting moving objects using a webcam feed. It uses OpenCV for image processing and contour detection to highlight motion in real-time.

## Features
- Captures live video from webcam
- Applies grayscale conversion and Gaussian blur
- Detects motion by comparing frames
- Highlights moving objects with bounding boxes
- Displays real-time video with detection overlay

##  How It Works
1. Capture video from webcam
2. Convert frames to grayscale and apply Gaussian blur
3. Use frame differencing to detect motion
4. Apply thresholding and dilation to isolate contours
5. Filter contours by area and draw bounding boxes around moving objects

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- imutils

Install dependencies using pip:
```bash
pip install opencv-python imutils
