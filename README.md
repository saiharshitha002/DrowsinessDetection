Driver drowsiness detection using deep learning
Driver drowsiness detection systems are designed to monitor the state of a driver in real-time and alert them when signs of drowsiness or fatigue are detected. These systems are crucial for ensuring driver safety, especially during long journeys or when driving at night.

Introduction
This project aims to develop a driver drowsiness detection system using deep learning techniques, particularly Convolutional Neural Networks (CNNs) with the ResNet50 architecture. The system detects drowsiness in real-time using a camera feed focused on the driver's face. It alerts the driver if signs of drowsiness are detected, helping to prevent accidents caused by driver fatigue.

Features
Real-time detection of driver drowsiness using a webcam feed.Utilizes ResNet50, a deep learning architecture known for its effectiveness in image recognition tasks.Alerts the driver with visual and/or auditory cues upon detecting signs of drowsiness.Can be integrated into existing automotive safety systems or standalone devices.

Requirements
Python 3.x
TensorFlow 2.x
OpenCV
NumPy
Matplotlib (for visualization, optional)
Pre-trained ResNet50 model (can be downloaded from the TensorFlow/Keras model zoo)

Installation
1.Clone or download the repository:
   git clone https://github.com/saiharshitha002/driver-drowsiness-detection.git
2.Install dependencies using pip:
   pip install -r requirements.txt
3.Download the pre-trained ResNet50 model from the TensorFlow/Keras model zoo and place it in the project directory.

Usage
1.Connect a webcam to your system.

2.Run the drowsiness_detection.py script:
    python drowsiness_detection.py
3.The script will open the webcam feed and start detecting drowsiness in real-time. If drowsiness is detected, it will display an alert message and/or sound an alarm.

Customization:
Adjust the sensitivity threshold for drowsiness detection by modifying parameters in the script.
Customize alert messages, sounds, or visual cues according to your preferences.

