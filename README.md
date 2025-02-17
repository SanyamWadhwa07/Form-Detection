# Form Detection

## Overview
**Form Detection** is an AI-powered application that utilizes **MediaPipe** and **computer vision** techniques to analyze and provide real-time feedback on exercise posture and form. The system helps users maintain correct posture during workouts, reducing the risk of injuries and improving training efficiency.

## Features
- **Real-time exercise form detection** using **MediaPipe**
- Provides **instant feedback** on user posture and movement
- Uses **computer vision** to track body key points and angles
- **Lightweight and efficient** implementation for seamless performance
- Designed for **fitness enthusiasts** and **athletes** to optimize workouts

## Requirements
To run this project, install the following dependencies:
- **Python** (v3.8+ recommended)
- **Flask** for backend development
- **OpenCV** for computer vision tasks
- **MediaPipe** for pose estimation
- **TensorFlow** (if required for AI-based enhancements)

### Install Required Packages
Run the following command to install dependencies:
```sh
pip install flask opencv-python mediapipe tensorflow
```

## Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/SanyamWadhwa07/Form-Detection.git
   cd Form-Detection
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the application:**
   ```sh
   python app.py
   ```

## Usage
- **Start the application** and allow camera access.
- **Perform exercises in front of the webcam**.
- The system will **detect your form and provide feedback**.

## Technologies Used
- **Backend:** Flask (Python)
- **Computer Vision:** OpenCV, MediaPipe
- **Machine Learning:** TensorFlow (if applicable)
- **Frontend:** HTML, CSS, JavaScript (for UI)

## Future Enhancements
- Add support for **more exercises and postures**.
- Improve **real-time feedback accuracy** using deep learning.
- Develop a **mobile-friendly version** for better accessibility.
