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
   git clone https://github.com/your-username/face-attendance-system.git
   cd face-attendance-system
2. **Create a virtual environment**
  `python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install dependencies**
`pip install -r requirements.txt`
4. **Run the Django server**
`python manage.py runserver`
