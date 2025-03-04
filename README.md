Facial Recognition with OpenCV
A beginner-friendly project exploring facial recognition using OpenCV. This project uses the Local Binary Patterns Histogram (LBPH) algorithm for face recognition and Haar Cascade for face detection. The system detects faces in real-time and recognizes known individuals.

📌 Table of Contents
Project Overview
Video Demo
Features
Technologies Used
Motivation and Purpose
Problem Statement and Objectives
Prerequisites
License
📌 Project Overview
This project demonstrates real-time facial recognition using a webcam. The system:

Detects faces using OpenCV's Haar Cascade classifier.
Recognizes faces using the LBPH (Local Binary Patterns Histogram) algorithm.
Displays the recognized person's name and confidence score.
🖥️ How It Works
The script loads a pre-trained Haar Cascade model for face detection.
It initializes an LBPH face recognizer and loads a trained model (lbph_classifier.yml).
The webcam captures video frames, detects faces, and recognizes known individuals.
Recognized faces are labeled with their names and confidence scores.
Press 'q' to exit the program.
📽️ Video Demo
(Add a link or GIF showcasing your project in action!)

🔹 Features
✔️ Real-time face detection and recognition
✔️ Uses OpenCV's Haar Cascade for face detection
✔️ Implements the LBPH algorithm for face recognition
✔️ Displays confidence scores for recognized faces
✔️ Supports multiple registered users
✔️ Runs on a live webcam feed

🛠️ Technologies Used
Python
OpenCV
Haar Cascade Classifier
Local Binary Patterns Histogram (LBPH) Face Recognizer
🎯 Motivation and Purpose
I wanted to learn how facial recognition works and understand how OpenCV handles face detection and recognition. This project helped me grasp the basics of computer vision and machine learning algorithms for face recognition.

📌 Problem Statement and Objectives
Problem Statement:
Facial recognition technology is widely used in security systems, attendance tracking, and authentication. The challenge was to implement a simple yet effective recognition system using OpenCV.

Objectives:
✔️ Understand the fundamentals of face detection & recognition.
✔️ Implement real-time facial recognition using OpenCV.
✔️ Train and test a face recognition model using LBPH.
✔️ Display names and confidence levels for recognized faces.

⚙️ Prerequisites
🔧 Installation
Ensure you have Python 3.x installed, then install the required libraries:

bash
Copy
Edit
pip install opencv-python opencv-contrib-python
▶️ Running the Project
Clone this repository:
bash
Copy
Edit
git clone https://github.com/yourusername/Facial-Recognition-OpenCV.git
cd Facial-Recognition-OpenCV
Run the face recognition script:
bash
Copy
Edit
python camera_lbph.py
Press 'q' to exit the program.
📜 License
This project is licensed under the MIT License – feel free to use and modify it.
