# Face-Detection-Using-OpenCV

👤 Face Detection using OpenCV (Python)

A real-time Face Detection project built using Python and OpenCV.
This application uses a Haar Cascade Classifier to detect human faces through a webcam and draws bounding boxes around detected faces.

🚀 Features

Real-time face detection using webcam

Uses OpenCV’s pre-trained Haar Cascade model

Simple and beginner-friendly implementation

Lightweight and fast execution

🛠️ Technologies Used

Python 3

OpenCV (cv2)

Haar Cascade Classifier

📂 Project Structure
face-detection-opencv/
│
├── face_detection.py
├── README.md

📦 Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/face-detection-opencv.git
cd face-detection-opencv

2️⃣ Install Required Libraries
pip install opencv-python


If you face issues with webcam:

pip install opencv-python-headless

▶️ How to Run the Project
python face_detection.py


A webcam window will open

Green rectangles will appear around detected faces

Press q to exit the application

🧠 How It Works

Captures live video using the system webcam

Converts frames to grayscale

Uses Haar Cascade Classifier to detect faces

Draws bounding boxes around detected faces

Displays the output in real-time

📸 Sample Output

Real-time face detection with bounding boxes drawn on detected faces.

(You can add a screenshot or GIF here)

⚠️ Requirements

Webcam (built-in or external)

Python 3.7+

OpenCV library

📌 Future Enhancements

Add eye and smile detection

Save detected face images

Face recognition using LBPH / Deep Learning

GUI using Tkinter or PyQt
