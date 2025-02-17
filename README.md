# GazePointer

This project implements an eye-controlled mouse using Python, OpenCV, and MediaPipe. The program tracks eye movement and blinks to move the mouse pointer and perform clicks on the screen.

### Features

- Tracks eye movement using MediaPipe's FaceMesh.

- Moves the mouse pointer based on eye gaze direction.

- Detects blinking to trigger a mouse click.

### Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x

- OpenCV (cv2)

- MediaPipe

- PyAutoGUI

### Installation

1. Clone this repository:

git clone [https://github.com/your-username/GazePointer.git](https://github.com/Sriramyabayyavarapu/GazePointer.git)
cd eye-controlled-mouse

2. Install dependencies:

pip install opencv-python mediapipe pyautogui

### Usage

Run the script:

python eye_controlled_mouse.py

### How It Works

- The webcam captures the user's face.

- MediaPipe detects facial landmarks.

- The script tracks specific eye landmarks to determine gaze direction.

- Mouse movement is controlled by the detected gaze direction.

- A blink (closing the eye for a short moment) triggers a mouse click.

### Demo

You can check out a demo of the eye-controlled mouse in action in the repository.

### Acknowledgments

- OpenCV

- MediaPipe

- PyAutoGUI

### License

This project is licensed under the MIT License.
