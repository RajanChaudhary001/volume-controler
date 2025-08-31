# volume-controler

🎵 Hand Gesture Volume Control

Control your PC volume using just your hand gestures 👋.
This project uses Python, OpenCV, and MediaPipe to detect hand landmarks and adjust the system volume in real-time.

📌 Features

✅ Real-time hand tracking with MediaPipe
✅ Control system volume by changing distance between thumb and index finger
✅ Visual volume bar and percentage overlay on camera feed
✅ Smooth & touchless interaction

🛠️ Tech Stack

Python 🐍

OpenCV – for camera and visualization

MediaPipe – for hand landmark detection

PyCaw – for system volume control (Windows only)

🚀 How It Works

Open the webcam using OpenCV

Detect hand landmarks using MediaPipe Hands

Measure distance between thumb tip and index fingertip

Map this distance to system volume range

Display volume bar + percentage on screen

📷 Demo

👉 [Add a screenshot or short GIF of your project here]

⚡ Installation

Clone the repository:

git clone https://github.com/your-username/hand-gesture-volume-control.git
cd hand-gesture-volume-control


Install dependencies:

pip install opencv-python mediapipe pycaw comtypes numpy


Run the script:

python volume_control.py

🎮 Usage

Show your hand in front of the webcam

Adjust distance between thumb & index finger:

Closer → Volume Down 🔉

Farther → Volume Up 🔊

Press ESC to exit

📌 Notes

Works only on Windows (because PyCaw is Windows-specific)

If webcam doesn’t open, try changing camera index in code:

cap = cv2.VideoCapture(1)

📜 License

This project is open-source and available under the MIT License.
