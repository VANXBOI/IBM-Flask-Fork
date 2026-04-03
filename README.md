# Repository for final project

Final Project
# Emotion Detection Web Application

## Overview
This project implements an end-to-end **Emotion Detection system** using IBM Watson NLP. It analyzes user-provided text and returns emotion scores along with the dominant emotion. The application is exposed via a Flask web interface and structured as a reusable Python package.

---

## Features
- Detects emotions: **anger, disgust, fear, joy, sadness**
- Identifies **dominant emotion**
- REST API integration with Watson NLP
- Flask-based web interface
- Modular package structure
- Unit tested
- Static code analysis compliant (PyLint 10/10)

---

## Project Structure
final_project/
│
├── server.py
├── test_emotion_detection.py
│
├── EmotionDetection/
│ ├── init.py
│ └── emotion_detection.py
│
├── templates/
│ └── index.html
│
└── static/
└── mywebscript.js
