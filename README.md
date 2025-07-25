# 🧠 Face Recognition-Based Attendance Management System

A robust and scalable attendance management solution powered by face recognition. Built using **Python**, **Django**, **Tkinter**, and **Deep Learning** techniques (DeepFace + MTCNN), this system ensures secure and real-time tracking of attendance across roles and environments.

## 📌 Features

- 🔍 **Facial Recognition Engine**
  - Real-time face detection using MTCNN.
  - Identity verification powered by DeepFace embeddings.
- 🔐 **Secure Role-Based Access Control**
  - Multi-user access with authentication and privilege management.
- 📊 **Intelligent Logging System**
  - Simultaneous logging to both CSV files and a relational database (PostgreSQL/MySQL).
  - Tracks timestamped events for auditing and reports.
- 🖥️ **Dual UI Architecture**
  - Desktop interface via Tkinter.
  - Django-powered admin portal for centralized control and insights.

## 🛠️ Technologies Used
## 🧰 Technologies Used

| Technology       | Description                                                                 | Icon Preview |
|------------------|-----------------------------------------------------------------------------|--------------|
| **Python**       | Core programming language for backend logic and integration                 | 🐍 ![Python](https://img.icons8.com/color/48/python.png) |
| **Django**       | Web framework for backend APIs and admin dashboard                          | 🌐 ![Django](https://img.icons8.com/color/48/django.png) |
| **Tkinter**      | GUI toolkit for desktop-based attendance interface                          | 🖥️ ![Tkinter](https://img.icons8.com/ios-filled/48/window.png) |
| **DeepFace**     | Facial recognition library for identity verification                        | 🧠 ![DeepFace](https://img.icons8.com/fluency/48/artificial-intelligence.png) |
| **MTCNN**        | Face detection model for accurate bounding box generation                   | 🎯 ![MTCNN](https://img.icons8.com/fluency/48/face-recognition.png) |
| **OpenCV**       | Computer vision library for image processing and camera interfacing         | 📷 ![OpenCV](https://img.icons8.com/color/48/opencv.png) |
| **PostgreSQL**   | Relational database for persistent attendance logging                       | 🗄️ ![PostgreSQL](https://img.icons8.com/color/48/postgresql.png) |
| **MySQL**        | Alternative relational database option                                      | 💾 ![MySQL](https://img.icons8.com/color/48/mysql-logo.png) |
| **Pandas**       | Data manipulation and CSV logging                                            | 📊 ![Pandas](https://img.icons8.com/color/48/pandas.png) |
| **TensorFlow**   | Deep learning framework for GPU-accelerated inference                       | ⚙️ ![TensorFlow](https://img.icons8.com/color/48/tensorflow.png) |
| **Keras**        | High-level neural network API used with TensorFlow                          | 🔧 ![Keras](https://img.icons8.com/color/48/keras.png) |
| **python-decouple** | Environment variable management for secure config handling              | 🔐 ![Decouple](https://img.icons8.com/fluency/48/settings.png) |

| Component            | Tool/Framework        |
|----------------------|-----------------------|
| Programming Language | Python                |
| GUI Framework        | Tkinter               |
| Web Framework        | Django                |
| Face Detection       | MTCNN                 |
| Face Recognition     | DeepFace              |
| Database             | PostgreSQL / MySQL    |
| Logging              | CSV + Relational DB   |

## 🚀 Setup & Installation

1. **Clone the repository**
   `bash
   git clone https://github.com/AbhayKushwaha29004/Face_Pulse-Serever-Room-Security-System.git
2. **Create a virtual environment**
  `python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install dependencies**
`pip install -r requirements.txt`
4. **Run the Django server**
`python manage.py runserver`
5. **Launch the Tkinter client**
   `python attendance_gui.py
