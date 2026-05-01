# Emotion Detection System

An AI-powered application that detects emotions from text using the Watson NLP library and provides a web interface via Flask.

## Project Details
This project implements an Emotion Detection application that analyzes text input to determine scores for various emotions (anger, disgust, fear, joy, and sadness) and identifies the dominant emotion.

## Features
- **Emotion Analysis:** Utilizes Watson NLP Emotion Predict service.
- **Web Interface:** Built with Flask for real-time analysis.
- **Error Handling:** Robust handling for empty inputs and server errors.
- **Unit Testing:** Comprehensive tests for different emotional states.
- **Packaging:** Modular design as a Python package.

## Installation
1. Clone the repository.
2. Install dependencies: `pip install flask requests`.
3. Run the server: `python3 server.py`.
