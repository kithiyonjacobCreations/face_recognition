# 👁️‍🗨️ Face Recognition and Surveillance System using OpenCV & ArcFace

A real-time face recognition and surveillance system developed using Python, OpenCV, and the ArcFace deep learning model. This project enables real-time face registration, recognition, and monitoring of known individuals, making it ideal for smart attendance systems, access control, and security surveillance.

## 🔍 Features

- 🔒 **Face Registration**: Register new users with name and face encoding
- 🧠 **Deep Learning Model**: Uses ArcFace (pre-trained) for robust face recognition
- 📷 **Live Video Detection**: Real-time face detection via webcam (OpenCV)
- 🎯 **Face Matching**: Identifies known faces from video feed
- 📁 **Database Management**: Stores facial embeddings with names for future recognition
- 📊 **Logging**: Records entry timestamps for recognized individuals


## ⚙️ How It Works

1. **Registration**:
   - Place your face in front of the camera.
   - The system captures your face and saves the embedding using ArcFace.
   - It associates the embedding with a user-defined name.

2. **Recognition**:
   - Runs a live webcam feed.
   - Detects and compares faces in real-time.
   - Displays the name if the face is recognized, otherwise shows "Unknown".

## 🧪 Technologies Used

- Python
- OpenCV
- ArcFace (InsightFace / ONNX / PyTorch version)
- NumPy
- Pickle (for storing embeddings)
- Face detection: RetinaFace / MTCNN / OpenCV Haarcascade (fallback)

## 🖥️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/kithiyonjacobCreations/face_recognition_project.git
cd face_recognition_project

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

install the requirments
run the main.py on ur terminal


