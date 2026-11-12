# OpenCV Color Detection

Real-time red color detection using Python and OpenCV. The program reads the webcam feed, finds red objects, and draws a green box around them.

## How it works

1. The webcam frame is converted from BGR to HSV color space.
2. A mask keeps only the red pixels.
3. Contours of the red regions are found.
4. A bounding box and label are drawn around each large red object.

## Requirements

- Python 3
- opencv-python
- numpy

Install them with:

    pip install opencv-python numpy

## How to run

    python color_detect.py

Press `q` in the camera window to quit.

## Author

Papun Behera
