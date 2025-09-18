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

###2. Install Dependencies

Install all the required Python libraries using pip. It's recommended to do this in a virtual environment.

```bash
pip install opencv-python mediapipe keyboard pycaw numpy

###3. Download the MediaPipe Model
* **The gesture recognition requires a model file from Google.

* **Download gesture_recognizer.task here - https://ai.google.dev/edge/mediapipe/solutions/vision/gesture_recognizer

* **Place the downloaded gesture_recognizer.task file in the root directory of this project (the same folder as the Python script).


###▶️ How to Use
Make sure your webcam is connected and not in use by another application.

Run the main Python script from your terminal:

```bash
python your_script_name.py

A window will appear showing your webcam feed. Perform the supported gestures to trigger actions.

To stop the program, make sure the webcam window is active and press the Esc key.

Note: The keyboard library may require administrator/root privileges to control other applications. You might need to run the script from an administrator terminal.

* **gestures
* **Gesture	Action
* **Index Finger Pointing Left	Holds the 'a' key
* **Index Finger Pointing Right	Holds the 'd' key
* **👍 Thumbs Up	Increases system volume
* **👎 Thumbs Down	Decreases system volume
* **✌️ Victory/Peace Sign	Opens a game in your web browser (once per session)

