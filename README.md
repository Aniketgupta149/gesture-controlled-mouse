# gesture-controlled-mouse
Control your mouse with hand gestures using OpenCV, MediaPipe, and PyAutoGUI. This virtual mouse tracks your index finger to move the cursor and uses a pinch gesture to click—no physical mouse needed!

# Virtual Mouse using Hand Gesture Recognition

This project uses **OpenCV**, **MediaPipe**, and **PyAutoGUI** to control the mouse using hand gestures detected through a webcam. It enables users to move the cursor with their index finger and perform a click gesture by bringing the thumb close to the index finger.

### Developed by: Aniket Harishchandra Gupta

---

## Features

- Real-time hand tracking using webcam.
- Cursor movement with index finger.
- Click action triggered by pinching motion (index and thumb fingers).

---

## Installation

Follow the steps below to set up and run the project on your system.

### 1. Clone or Download the Repository

If you have Git installed:
```bash
git clone https://github.com/Aniketgupta149/virtual-mouse-gesture.git
cd virtual-mouse-gesture
```
Or download and extract the ZIP file, then navigate to the extracted folder.

### 2. Set Up Python Environment

Make sure Python 3.7+ is installed. You can install dependencies in a virtual environment (recommended):

```bash
python -m venv venv
venv\Scripts\activate     # On Windows
source venv/bin/activate  # On Linux/macOS
```

### 3. Install Required Libraries

Install the necessary Python libraries using pip:

```bash
pip install opencv-python mediapipe pyautogui
```

---

## Running the Project

Once dependencies are installed, you can run the script using:

```bash
python main.py
```

### Notes:
- Ensure your webcam is connected and working.
- Grant the application access to control the mouse (especially on macOS).
- A window titled **"Virtual Mouse"** will open showing the webcam feed with hand landmarks drawn in real-time.

---

## Controls

- **Move Cursor:** Move your index finger in front of the camera.
- **Click:** Bring your thumb close to the index finger (pinch gesture).

---

## Troubleshooting

- If the camera feed doesn't appear, check if another app is using the webcam.
- Ensure all required libraries are installed correctly.
- On high-resolution screens, pointer movement may need fine-tuning for precision.

---

## License

This project is open-source and free to use for learning and educational purposes.

---

## Author

**Aniket Harishchandra Gupta**  
📧 [ag1499459@gmail.com](mailto:ag1499459@gmail.com)  
🔗 [Portfolio](https://aniket-portfolio149.web.app)  
💼 [LinkedIn](https://www.linkedin.com/in/aniket-gupta-b44611261)  
💻 [GitHub](https://github.com/Aniketgupta149)
