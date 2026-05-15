
## Overview
This project implements a real-time human facial emotion detection system using deep learning and NVIDIA Jetson Nano. The system captures facial expressions through a camera, processes the image using computer vision techniques, and predicts human emotions using a Convolutional Neural Network (CNN).

The project is designed for edge AI applications where low-power and real-time inference are required.

---

## Objectives
- Detect human faces in real time
- Recognize facial emotions accurately
- Deploy deep learning model on NVIDIA Jetson Nano
- Implement lightweight edge AI inference

---

## Features
- Real-time emotion recognition
- CNN-based deep learning model
- OpenCV-based face detection
- Edge AI deployment on Jetson Nano
- Live camera input processing
- Lightweight and efficient system

---

## Emotions Detected
- Happy
- Sad
- Angry
- Neutral
- Surprise
- Fear
- Disgust

---

## Hardware Requirements
- NVIDIA Jetson Nano
- USB Camera / Webcam
- Monitor and peripherals
- SD Card (32 GB recommended)

---

## Software Requirements
- Python 3.x
- OpenCV
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## Technologies Used
- Python
- Deep Learning
- CNN
- OpenCV
- Computer Vision
- NVIDIA Jetson Nano
- Edge AI

---

## Project Structure

```bash
Human-emotion-detection-using-jetson-nano/
│
├── dataset/
├── model/
├── src/
│   ├── train.py
│   ├── detect_emotion.py
│   └── utils.py
│
├── outputs/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/manyarajeevan47-arch/Human-emotion-detection-using-jetson-nano.git
```

### Navigate to Project Folder

```bash
cd Human-emotion-detection-using-jetson-nano
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

```bash
python detect_emotion.py
```

---

## Dataset
The model is trained using facial emotion datasets containing labeled facial expressions for different emotions.

Example datasets:
- FER2013
- CK+
- RAF-DB

---

## Future Improvements
- Improve model accuracy
- Add TensorRT optimization
- Multi-face emotion detection
- Emotion analytics dashboard
- Mobile application integration

---

## Applications
- Human-computer interaction
- Smart surveillance systems
- Mental health monitoring
- Driver monitoring systems
- AI assistants and robotics

---

## Results
The system performs real-time emotion recognition with optimized inference on NVIDIA Jetson Nano for edge deployment.

---

## Author
### Manya Rajeevan
Electronics and Communication Engineering

---

## License
This project is licensed under the MIT License.
