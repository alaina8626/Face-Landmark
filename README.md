**Real-Time Multi-Face Mesh Detection using MediaPipe and OpenCV**

This project performs real-time facial landmark detection using MediaPipe Face Mesh and OpenCV. It supports detection of up to 5 faces simultaneously and renders 468 3D facial landmarks per face with detailed tesselation.


🔧 Features:
Real-time webcam feed with flipped (mirror) display
Detects and tracks up to 5 faces simultaneously
Draws facial mesh tesselation using 468 landmarks
Uses refined landmarks for better accuracy

🚀 Installation:
Prerequisites
Make sure you have Python 3.7 or higher installed. Then, install the required libraries:
_pip install opencv-python mediapipe_

📦 Usage:
Run the Python script-
_python face_mesh_detection.py_
Press p to exit the webcam window.

🧠 How It Works:
MediaPipe Face Mesh detects facial landmarks in real time.
OpenCV handles video capture and drawing.
The frame is flipped horizontally for a mirror-like view.

Output:
Each detected face is overlaid with a facial mesh made of fine-grained landmarks:
468 face landmarks
Dense mesh rendering via FACEMESH_TESSELATION
Adjustable drawing specs (thickness, circle_radius)

