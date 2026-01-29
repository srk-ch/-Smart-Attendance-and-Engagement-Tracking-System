Idea 1.0: 
Drive link: 
#Enagage Predict: Smart Attendance and Engagement Tracking System
# Fortex VS

Welcome to the Fortex VS project! This repository contains the source code and resources for the Fortex VS application, which is designed to provide advanced engagement prediction and analysis using computer vision and machine learning.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Advanced engagement prediction using machine learning models.
- Real-time camera-based emotion tracking.
- Comprehensive deployment guides for production readiness.
- Backend API for integration with other systems.
- Frontend interface for user interaction.
- Dockerized setup for easy deployment.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fortex-vs.git
   cd fortex-vs
   ```

2. Set up the virtual environment:

   ```powershell
   python -m venv .venv
   & .venv\Scripts\Activate.ps1
   ```

3. Install the required dependencies:

   ```bash
   pip install -r backend/requirements.txt
   npm install --prefix frontend
   ```

4. Start the backend server:

   ```bash
   python backend/app.py
   ```

5. Start the frontend application:

   ```bash
   npm start --prefix frontend
   ```

## Usage

1. Ensure the backend server and frontend application are running.
2. Access the application in your web browser at `http://localhost:3000`.
3. Follow the on-screen instructions to use the engagement prediction and analysis features.

## Project Structure

```
fortex-vs/
├── backend/
│   ├── advanced_endpoints.py
│   ├── advanced_model.py
│   ├── app.py
│   ├── config.py
│   ├── database.py
│   ├── requirements.txt
│   └── ...
├── frontend/
│   ├── App.css
│   ├── index.css
│   ├── index.jsx
│   ├── package.json
│   └── ...
├── docker-compose.yml
├── setup.ps1
├── setup.sh
└── README.md

Idea 2:
Drive link:https://drive.google.com/file/d/1EIpiB3aRBeSBuBJz6c2NSfpDSuTgWt1j/view?usp=sharing
This drive link has the whole environment included all u need is to run start.bat in the terminal and you are good to go for lauching it
# CollabVibe: Smart Attendance and Engagement Tracking System

## Overview
CollabVibe is a comprehensive platform designed to automate attendance and track engagement in educational and organizational settings. It goes beyond traditional attendance by analyzing participation, engagement, and consistency, providing actionable insights to improve learning and collaboration outcomes.

## Features
- **Automated Attendance:** No manual roll call; presence is logged based on user activity.
- **Engagement Analytics:** Uses AI/ML to score participation using video, audio, and interaction data.
- **Consistency Tracking:** Monitors patterns over time to identify consistent and inconsistent participants.
- **Real-Time Dashboards:** Visualizes attendance, engagement, and trends for users and administrators.
- **Optional AI Models:** Emotion detection (TensorFlow + DeepFace), speech transcription (Whisper), and AI insights (Transformers).
- **Secure & Extensible:** JWT authentication, modular codebase, and Docker support.

## Technology Stack
- **Frontend:** React, Tailwind CSS, Node.js
- **Backend:** FastAPI, Uvicorn, Python
- **Database:** SQLite (default, can be upgraded)
- **AI/ML:** CatBoost, scikit-learn, MediaPipe, TensorFlow (optional)
- **Other:** Docker, WebSockets, VADER Sentiment

## Project Structure
```
demo.py
start.bat
docker-compose.yml
backend/
  Dockerfile
  main.py
  requirements.txt
  ...
frontend/
  Dockerfile
  package.json
  src/
    App.js
    ...
```

## Quick Start
### Prerequisites
- Python 3.8+
- Node.js 16+
- (Optional) Docker

### One-Click Setup (Windows)
Run `start.bat` from the project root. This will:
- Check for Python and Node.js
- Set up a Python virtual environment and install backend dependencies
- Optionally install AI models (TensorFlow, DeepFace, Whisper, Transformers)
- Install frontend dependencies
- Start backend (http://localhost:8000) and frontend (http://localhost:3000)

### Manual Setup
#### Backend
```
cd backend
python -m venv venv
venv\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
# (Optional) Install AI models as needed
python main.py
```
#### Frontend
```
cd frontend
npm install
npm start
```

### Docker (Optional)
```
docker-compose up --build
```

## Usage
- Access the frontend at [http://localhost:3000](http://localhost:3000)
- Backend API docs at [http://localhost:8000/docs](http://localhost:8000/docs)
- Default ports: 3000 (frontend), 8000 (backend)

## Customization
- To enable advanced AI features, choose 'y' when prompted during setup or manually install the required packages.
- Configuration files for backend and frontend are located in their respective folders.

## Troubleshooting
- If you see "Network Error" on the frontend:
  1. Ensure both backend and frontend terminals are running
  2. Visit http://localhost:8000/health to check backend status
  3. Check backend output for errors
  4. Refresh the frontend page

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)

## Acknowledgements
- FastAPI, React, CatBoost, scikit-learn, MediaPipe, TensorFlow, VADER Sentiment, and all open-source contributors.

---

**Developed for FORTEX National Hackathon**


