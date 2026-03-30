# Color Tracker using OpenCV

## Overview
This project is a real-time color tracking system built using Python and OpenCV.  
It detects a specific color (red) from the webcam feed and highlights it with a bounding box.

## Problem Statement
In many real-world scenarios like object tracking, robotics, and computer vision, detecting specific colors is important.  
This project solves the problem of identifying and tracking a colored object in real-time using a webcam.

## Features
- Real-time video capture using webcam
- Detects red color using HSV color space
- Draws bounding box around detected object
- Filters noise using contour area threshold
- Displays both live video and mask

## Technologies Used
- Python
- OpenCV (cv2)
- NumPy

## Requirements
- Python 3.x
- OpenCV
- NumPy

## Installation

1. Install required libraries:
   pip install opencv-python numpy

2. Run the program:
   python colortrackcode.py

## How It Works
- The webcam captures live video
- Frame is converted from BGR to HSV color space
- Red color is detected using two HSV ranges
- Mask is created to isolate red color
- Contours are detected from the mask
- Bounding box is drawn around detected object

## Controls
- Press **q** to exit the program

## File Structure
- colortrackcode.py → Main program file

## Future Improvements
- Support for multiple colors
- Object tracking with ID
- GUI interface
- Integration with AI models

## Conclusion
This project demonstrates basic computer vision techniques such as color detection, masking, and contour detection in real time.
