# Virtual-Mouse

## Project Description
This project implements a virtual mouse using hand tracking with Mediapipe and OpenCV, enabling control of the mouse cursor and clicks through hand gestures. The project uses Python and Pyautogui for mouse automation.

## Features
- Hand Tracking: Utilizes Mediapipe to detect and track hand movements in real-time.
- Cursor Control: Move the mouse cursor using your hand.
- Click Actions: Perform left and right-click actions through specific hand gestures.
- Easy Setup: Simple and straightforward code for quick setup and usage.

## Requirements
- Python 3.x
- OpenCV
- Mediapipe
- Pyautogui

## How It Works
Hand Detection: Mediapipe is used to detect and track the hand in real-time using the webcam feed.
Landmark Extraction: Key landmarks on the hand are identified to track movements and gestures.
Gesture Recognition: Specific hand gestures are mapped to mouse actions (e.g., moving the cursor, left-click, right-click).
Mouse Control: Pyautogui is used to control the mouse cursor and perform click actions based on the recognized gestures.
