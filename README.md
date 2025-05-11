# MediaPlayer-GestureCtrl-
A simple Python-based media player that currently supports volume control — allowing users to increase or decrease the system volume using Python scripts. The project consists of three Python files demonstrating the basic functionality.


# 🎚️ Hand Gesture Volume Control

Control your system's volume using just your hand gestures via webcam, powered by MediaPipe and Pycaw.

## 🚀 Features

- Real-time hand tracking with MediaPipe
- Controls volume using distance between thumb and index finger
- Live volume bar and percentage display
- FPS (Frames Per Second) counter
- Works with internal or external webcam

## 🛠️ Technologies Used

- Python 3
- OpenCV
- MediaPipe
- NumPy
- Pycaw (for Windows audio control)

## 💡 How It Works

1. Uses MediaPipe to detect hand and finger landmarks.
2. Measures the distance between the thumb tip and index finger tip.
3. Maps that distance to a volume range using interpolation.
4. Adjusts the system's master volume accordingly using Pycaw.
5. Displays volume level and FPS on the screen.

## 📦 Installation

Install the required libraries using pip:


> If you are using an internal webcam, change `cv2.VideoCapture(1)` to `cv2.VideoCapture(0)` in the code.

## ✅ Notes

- Only works on Windows (due to Pycaw dependency).
- Ensure your webcam has access permission.
- Adjust hand distance slowly for more precise volume control.

## 📄 License

This project is licensed under the MIT License.

---

Made with ❤️ using Python and OpenCV

