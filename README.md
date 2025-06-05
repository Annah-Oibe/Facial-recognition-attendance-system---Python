# 👤 Facial Recognition Attendance System (Python)

An intelligent attendance management system using facial recognition powered by OpenCV and Python. This system captures real-time images from a webcam, recognizes faces, and logs attendance with timestamps into a CSV file. Built with simplicity, efficiency, and extensibility in mind.

---

## 📌 Features

- ✅ Real-time face detection and recognition
- ✅ Attendance logging with timestamps
- ✅ User registration with image capture
- ✅ Trained face model using LBPH (OpenCV)
- ✅ Admin dashboard (Flask/Tkinter)
- ✅ Prevents duplicate entries per session
- ✅ (Optional) Anti-spoofing for liveness detection

---

## 🛠️ Tech Stack

- **Language**: Python 3.13+
- **Libraries**: 
  - OpenCV
  - NumPy
  - Pandas
  - Flask or Tkinter (for GUI)
  - scikit-learn (optional, for KNN recognition)
  - Mediapipe (optional, for anti-spoofing)

---

## 📁 Project Structure
FacialRecognitionAttendance/
- dataset/ # Stored user face images
- trainer/ # Trained face recognition model
- attendance/ # CSV logs of attendance
- static/ # (Flask) CSS, JS, images
- templates/ # (Flask) HTML templates
- 
-  app.py # Flask main app
-  capture_faces.py # User registration
- train_model.py # Model training script
-  recognize.py # Real-time recognition
-  utils.py # Utility functions
-  requirements.txt # Required Python packages
-  README.md # Project documentation

---

## ✍️ Authors section
- **Annah Oibe** - annahoibe@gmail.com
- **Jesse Dangana** - http://github.com/mubarraqqq
- **Olawoye Oluwanifemi** - http://github.com/Nife06

##Installation

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/facial-recognition-attendance-system.git
cd facial-recognition-attendance-system




