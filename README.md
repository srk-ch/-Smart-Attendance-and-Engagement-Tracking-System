
# 🚀 Fortex VS

### Smart Attendance & Engagement Tracking System

**Developed for FORTEX National Hackathon**

🔗 **Complete Project Drive Link (Environment + Setup Included):**
👉 **https://drive.google.com/file/d/1EIpiB3aRBeSBuBJz6c2NSfpDSuTgWt1j/view?usp=drive_link**

> 📦 The Drive link contains the **entire working environment**
> ▶️ Just run `start.bat` and the system launches automatically

---

## 📌 Overview

**Fortex VS** is an AI-powered system that **automates attendance and predicts engagement** in classrooms and collaborative environments.
It goes beyond presence tracking by analyzing **attention, emotion, participation, and consistency**, enabling **real-time insights and proactive intervention**.

---

## 🧠 Idea 1.0

## **Engage Predict: Smart Attendance & Engagement Tracking System**

**Engage Predict** focuses on **predictive disengagement detection** using machine learning and computer vision.
The system analyzes behavioral signals to **identify early signs of disengagement** and provides insights that help improve learning outcomes.

### 🔹 Core Capabilities

* Machine-learning based engagement prediction
* Real-time camera-based emotion & attention analysis
* Backend APIs for analytics integration
* Interactive frontend dashboards
* Dockerized deployment for easy setup
fortex-vs/
├── backend/
│   ├── app.py                  # Backend entry point
│   ├── advanced_model.py       # ML-based engagement prediction
│   ├── advanced_endpoints.py   # Analytics & prediction APIs
│   ├── database.py             # Attendance & engagement storage
│   ├── config.py               # Environment configuration
│   ├── requirements.txt        # Backend dependencies
│   └── ...
├── frontend/
│   ├── src/
│   │   ├── components/         # UI components
│   │   ├── pages/              # Engagement dashboards
│   │   └── services/           # API connectors
│   ├── App.jsx
│   ├── index.jsx
│   └── package.json
├── docker-compose.yml
├── setup.ps1                   # Windows setup
├── setup.sh                    # Linux/Mac setup
└── README.md

---

## 🧠 Idea 1.1

## **Bright Presence: Smart Attendance & Engagement Tracking System**

### 🔍 Executive Summary

**BrightPresence** is a real-time AI classroom monitoring system designed to help educators understand **who is present, who is engaged, and who needs support**—while sessions are still ongoing.

It combines **computer vision + ML + real-time dashboards** to provide actionable insights and intelligent nudges.

---

### 👩‍🏫 Teacher Features

* Automated attendance (no roll calls)
* Live engagement surveillance dashboard
* One-click session start & stop
* Session-end engagement reports
* Instant flags for low engagement

### 🎓 Student Features

* Real-time engagement indicators (Attention, Gaze, Emotion)
* Smart nudges when focus drops
* Secure login with face-based verification

---

### 🏗️ Technical Architecture

#### Backend

* **FastAPI** for async APIs & WebSockets
* **OpenCV + MediaPipe** for face & gaze tracking
* **DeepFace** for emotion analysis
* **Scikit-learn** for engagement scoring
* **SQLite + SQLAlchemy** for persistence

#### Frontend

* **React.js** (Vite)
* **Tailwind CSS**
* Real-time WebSocket updates
* Separate dashboards for teachers & students

---

### 🔁 Session Workflow

1. Teacher logs in & starts a session
2. Students join and enable camera
3. Live analysis of attention, emotion & gaze
4. Scores streamed to dashboards
5. Automatic nudges on disengagement
6. Session ends → report generated

---

### 🔮 Future Roadmap

* Long-term engagement trend analytics
* Privacy-first (client-side only) mode
* LMS integration (Canvas, Moodle, etc.)
bright-presence/
├── backend/
│   ├── main.py                 # FastAPI entry point
│   ├── models.py               # Users, sessions, logs
│   ├── services/
│   │   ├── vision_engine.py    # Face, gaze & emotion analysis
│   │   ├── scoring_engine.py   # Engagement scoring logic
│   │   └── nudge_engine.py     # Smart intervention triggers
│   ├── database.py             # SQLite + ORM
│   └── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── TeacherDashboard.jsx
│   │   │   ├── StudentDashboard.jsx
│   │   │   └── Auth.jsx
│   │   ├── components/
│   │   └── hooks/
│   ├── tailwind.config.js
│   └── package.json
└── README.md

---

## 🧠 Idea 2

## **CollabVibe: Smart Attendance & Engagement Tracking System**

**CollabVibe** is the **final unified implementation**, combining the strongest ideas from EngagePredict and BrightPresence into a **production-ready, modular platform**.

This is the **version included in the Drive link and GitHub repository**.

---

### ✨ Features

* Automated attendance via session activity
* AI-driven engagement scoring
* Participation & consistency tracking
* Real-time dashboards
* Optional AI modules (Emotion, Speech, NLP)
* Secure JWT-based authentication
* Docker support for deployment

---

### 🧰 Technology Stack

**Frontend**

* React.js
* Tailwind CSS
* Node.js

**Backend**

* FastAPI
* Uvicorn
* Python

**Database**

* SQLite (upgradeable)

**AI / ML**

* CatBoost
* Scikit-learn
* MediaPipe
* DeepFace (optional)
* Whisper & Transformers (optional)

---

### 📁 Project Structure (Actual Repository)

```
COLLABVIBE/
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   ├── requirements.core.txt
│   ├── requirements.ai.txt
│   ├── Dockerfile
│   ├── collabvibe.db
│   └── ...
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── DashboardPage.js
│   │   │   ├── LandingPage.js
│   │   │   └── SessionPage.js
│   │   └── App.js
│   ├── tailwind.config.js
│   └── package.json
├── docker-compose.yml
├── demo.py
└── start.bat
```

---

### ⚡ Quick Start (Recommended)

#### 🪟 One-Click Setup (Windows)

```bash
start.bat
```

✔ Automatically sets up backend & frontend
✔ Installs dependencies
✔ Starts servers

---

### 🔧 Manual Setup

#### Backend

```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

#### Frontend

```bash
cd frontend
npm install
npm start
```

---

### 🌐 Access

* Frontend → [http://localhost:3000](http://localhost:3000)
* Backend API → [http://localhost:8000/docs](http://localhost:8000/docs)

---

## 🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first.

---

## 📜 License

MIT License

---

## 🙌 Acknowledgements

FastAPI, React, CatBoost, Scikit-learn, MediaPipe, DeepFace, Whisper, TensorFlow, and the open-source community.

---


