# Drowsiness Detection using Raspberry Pi and Python

## 🚀Description
A Python-based drowsiness detection system using a Raspberry Pi and computer vision techniques to monitor a person's eye blinking patterns and determine their alertness level.

## Requirements
- Raspberry Pi
- Python programming language
- OpenCV library (`cv2`)
- NumPy library (`numpy`)
- dlib library for face detection and shape prediction
- imutils library for face utilities
- RPi.GPIO library for controlling GPIO pins
- shape_predictor_68_face_landmarks.dat file

## 🔍Code Overview
- Import necessary libraries and modules.
- Initialize the camera capture and dlib's face detector and shape predictor.
- Define functions for calculating Euclidean distance between points and detecting eye blinking patterns.
- Set up GPIO pins for the buzzer.
- Continuously capture frames from the camera and process them.
- Detect faces in the frame and draw rectangles around them.
- Calculate eye aspect ratios to determine blinking patterns.
- Based on blinking patterns, update the person's alertness status.
- Display the status on the frame with appropriate colors and activate the buzzer when needed.
- Display the processed frames with status indicators and face detection rectangles.
- Exit the loop on pressing the 'esc' key.
- Clean up GPIO pins and close the OpenCV windows on exit.

## 🔧Customization
- You can adjust the blinking thresholds and time limits for determining alertness levels.
- Modify the GPIO pin numbers for the buzzer according to your setup.
