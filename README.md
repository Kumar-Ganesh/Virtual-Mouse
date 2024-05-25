# Virtual-Mouse
Virtual Mouse Using OpenCV, Mediapipe, Pyautogui
This project implements a virtual mouse using hand tracking with Mediapipe and OpenCV, enabling control of the mouse cursor and clicks through hand gestures. The project uses Python and Pyautogui for mouse automation.

Features
Hand Tracking: Utilizes Mediapipe to detect and track hand movements in real-time.
Cursor Control: Move the mouse cursor using your hand.
Click Actions: Perform left and right-click actions through specific hand gestures.
Easy Setup: Simple and straightforward code for quick setup and usage.
Requirements
Python 3.x
OpenCV
Mediapipe
Pyautogui
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/virtual-mouse-opencv-mediapipe.git
cd virtual-mouse-opencv-mediapipe
Create and activate a virtual environment (optional but recommended):

sh
Copy code
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the required packages:

sh
Copy code
pip install -r requirements.txt
Usage
Run the following command to start the virtual mouse:

sh
Copy code
python virtual_mouse.py
How It Works
Hand Detection: Mediapipe is used to detect and track the hand in real-time using the webcam feed.
Landmark Extraction: Key landmarks on the hand are identified to track movements and gestures.
Gesture Recognition: Specific hand gestures are mapped to mouse actions (e.g., moving the cursor, left-click, right-click).
Mouse Control: Pyautogui is used to control the mouse cursor and perform click actions based on the recognized gestures.
Customization
Adjusting Sensitivity:
You can modify the sensitivity of the cursor movement by changing parameters in the code.
Adding New Gestures:
You can add new gestures and map them to different mouse actions by updating the gesture recognition logic.
Project Structure
bash
Copy code
virtual-mouse-opencv-mediapipe/
├── virtual_mouse.py          # Main script for the virtual mouse
├── requirements.txt          # Python package requirements
├── README.md                 # Project documentation
└── examples/                 # Directory with example usage and demo videos
