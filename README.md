Face Recognition System using OpenCV & Python
📌 Project Overview

This project implements a real-time face recognition system using OpenCV and Python. It detects human faces from a webcam feed using Haar Cascade Classifier and recognizes individuals using the LBPH (Local Binary Pattern Histogram) face recognizer.

The system also includes a basic Tkinter GUI for dataset generation and training, making it suitable for academic demonstrations and beginner-level AI applications.

🎯 Problem Statement

Manual identification of individuals is time-consuming and error-prone. This project aims to automate face identification using computer vision techniques that can work efficiently on small datasets and in real-time environments.

🧠 Technologies Used

Python

OpenCV

NumPy

Pillow (PIL)

Tkinter

Jupyter Notebook

🏗️ Project Architecture

Capture face images using webcam

Detect faces using Haar Cascade classifier

Convert images to grayscale

Train LBPH face recognizer

Save trained model (classifier.xml)

Load model for real-time recognition

Predict face and display result

📁 Folder Structure
Face-recognition/
│
├── data/                     # Face image datasets
├── classifier.xml             # Trained face recognition model
├── haarcascade_frontalface_default.xml
├── Face recognizer.ipynb      # Core face recognition logic
├── GUI face recognizer.ipynb  # GUI for training and detection
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation

▶️ How to Run the Project
1️⃣ Install Dependencies

Open Command Prompt in the project folder and run:

pip install -r requirements.txt

2️⃣ Run Face Recognition

Open Jupyter Notebook and execute:

Face recognizer.ipynb

This will:

Open webcam

Detect faces

Recognize trained faces in real time

3️⃣ (Optional) Run GUI

Run:

GUI face recognizer.ipynb

The GUI allows:

Dataset generation

Training the model

Face detection via interface

📸 Output

Real-time face detection using webcam

Face recognition with bounding box and label

GUI-based dataset generation

(Screenshots or demo video can be added here)

🚀 Future Improvements

Improve recognition accuracy with larger datasets

Add deep learning models (CNN / FaceNet)

Improve GUI design

Add database integration for identity storage

🧑‍💻 Author

Gurijala Tej Kumar
B.Tech – Computer Science Engineering
2026 Batch

📌 Key Learning Outcomes

Hands-on experience with OpenCV

Understanding of face detection vs recognition

Model training and deployment

Real-time computer vision applications