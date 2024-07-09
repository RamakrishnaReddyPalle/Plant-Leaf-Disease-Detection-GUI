# **Leaf Disease Prediction App**

### Overview

This project implements an end-to-end solution for predicting leaf disease types using deep learning. The application includes both a desktop GUI app and a web app (CURRENTLY UNDER DEVELOPMENT), allowing users to upload leaf images and receive predictions on the type of disease affecting the plant.

### Features

- **Desktop GUI App**: Utilizes `tkinter` and `ttkbootstrap` for a user-friendly interface on desktop systems.
- **Web App**: Built with `Flask` to provide a web-based interface accessible from browsers.

### Deployment

- **Desktop App**: UsING `PyInstaller` or similar tools for bundling.
- **Web App**: Deploy on platforms like Heroku or AWS Elastic Beanstalk.

### Usage

1. **Desktop App**:
   - Install necessary dependencies (`tkinter`, `ttkbootstrap`).
   - Run `python main.py` to launch the desktop GUI app.

2. **Web App**:
   - Install dependencies (`Flask`, `tensorflow`, etc.).
   - Set up the environment (`venv`, configurations).
   - Run `python app.py` to start the Flask server.
   - Access the app via browser at `http://localhost:5000`.

### Requirements

- Python 3.x
- TensorFlow, Flask, tkinter (for desktop app), ttkbootstrap (for modern GUI design), and other dependencies as listed in `requirements.txt`.


---
