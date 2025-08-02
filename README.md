# FACE-DETECTION
🧠 Face Detection System

This is a face detection system built using OpenCV and Python. It uses a Haar Cascade classifier to detect faces from a webcam in real-time and stores the face data for further use.


---

📁 Project Structure

FACE-DETECTION/
│
├── face_detectionn/               # Contains main Python files for face detection
│   ├── collect_data.py            # To collect face data from webcam
│   ├── consolidated.py            # Runs the detection and recognition logic
│   ├── haarcascade_frontalface_default.xml # Haar Cascade model file
│   └── labels.p                   # Pickled labels for faces
│
├── README.md                      # Project explanation file


---

⚙ Requirements

Install the following Python libraries before running:

pip install opencv-python


---

▶ How to Run

1. Run collect_data.py to collect face images from webcam.


2. Run consolidated.py to detect and recognize faces.
