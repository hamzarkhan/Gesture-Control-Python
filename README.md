# 🐍 Python Gesture Controller

Control your computer's actions, like game movements and system volume, using hand gestures recognized in real-time through your webcam. This project uses OpenCV for video capture and Google's MediaPipe for powerful hand tracking and gesture recognition.

---

## ✨ Features

* **🎮 Game Control**: Point your index finger left or right relative to your wrist to simulate holding the **'a'** and **'d'** keys for in-game movement.
* **🔊 Volume Control**: Raise or lower your system's master volume with a **thumbs-up** 👍 or **thumbs-down** 👎 gesture.
* **🚀 Launch Action**: Make a **victory/peace sign** ✌️ to open a web game in your browser.

---

## 📋 Requirements

* Python 3.7+
* A webcam
* **Windows OS** (The `pycaw` library for volume control is Windows-specific.)

---

## 🛠️ Setup and Installation

Follow these steps to get the project running.

### 1. Clone the Repository

Clone this repository to your local machine:
```bash
git clone [https://github.com/YOUR_USERNAME/Gesture-Control-Python.git](https://github.com/YOUR_USERNAME/Gesture-Control-Python.git)
cd Gesture-Control-Python

## 🛠️ Setup and Installation

### 2. Install Dependencies

Install all the required Python libraries using pip. It's recommended to do this in a virtual environment.

```bash
pip install opencv-python mediapipe keyboard pycaw numpy

### 3. Download the MediaPipe Model

The gesture recognition requires a model file from Google.

- **Download the model file here**: [`gesture_recognizer.task`](https://ai.google.dev/edge/mediapipe/solutions/vision/gesture_recognizer)
- **Placement**: After downloading, place the `gesture_recognizer.task` file in the **root directory** of this project (the same folder as your main Python script).
