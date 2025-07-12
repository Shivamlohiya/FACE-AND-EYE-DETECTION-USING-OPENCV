# FACE-AND-EYE-DETECTION-USING-OPENCV

This project uses **OpenCV** and **Haar Cascade classifiers** to detect faces and eyes in real-time from a webcam feed. It demonstrates how classical computer vision techniques can be used for surveillance, authentication, and human-computer interaction.

## 📌 Project Overview

Face and eye detection is a foundational task in computer vision. This project captures live video, detects faces and eyes using pre-trained Haar cascades, and highlights them with bounding boxes. It’s fast, lightweight, and ideal for real-time applications.

## 🚀 Features

- Detects faces and eyes from live webcam feed
- Uses Haar cascade classifiers for efficient detection
- Draws bounding boxes around detected regions
- Real-time performance with minimal latency
- Clean exit on key press

## 🧠 Techniques Used

| Technique              | Purpose                                      |
|------------------------|----------------------------------------------|
| Haar Cascade Classifier| Pre-trained XML models for face/eye detection|
| `cv2.VideoCapture()`   | Captures live webcam feed                    |
| `cv2.CascadeClassifier()`| Loads Haar models                          |
| `cv2.detectMultiScale()`| Detects objects in image                    |
| `cv2.rectangle()`      | Draws bounding boxes                         |

## 🛠️ Tech Stack

- **Language**: Python
- **Library**: OpenCV
- **Tools**: VS Code, Jupyter Notebook 

