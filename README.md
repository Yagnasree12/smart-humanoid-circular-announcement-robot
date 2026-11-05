# 🤖 Smart Humanoid Circular Announcement Robot

## 📌 Project Overview

The **Smart Humanoid Circular Announcement Robot** is a robotics-based project designed to improve circular announcement delivery in educational institutions.

Traditionally, staff members need to visit classrooms manually to communicate important circulars, which can cause delays, increase workload and interrupt ongoing academic activities.

To address these challenges, this project proposes a smart humanoid robot integrated with a mobile application. Users can upload circular documents through the application, and the system extracts the text using Tesseract OCR. The extracted content is converted into speech using the pyttsx3 Text-to-Speech (TTS) engine.

The robot navigates to designated classrooms using SLAM-based mapping and localization and delivers announcements through a speaker.

## 🎯 Problem Statement

Manual classroom announcement systems are time-consuming and depend heavily on staff availability. This project aims to provide a technology-driven solution for efficient, timely and consistent announcement delivery across educational institutions.

## ✨ Key Features

- Mobile application-based circular uploading.
- Speech processing using PyAudio, Voice Activity Detection (VAD) and MFCC techniques.
- Text extraction from uploaded circulars using Tesseract OCR.
- Indoor mapping and localization using SLAM.
- Robot navigation using RPLIDAR C1 and ROS2.
- Obstacle detection and avoidance.
- Text-to-Speech announcement delivery using pyttsx3.
- Repeat announcement functionality.
- Announcement completion notifications.

## 🛠️ Technology Stack

**Programming Language**
- Python 3

**Operating System**
- Ubuntu 24.04

**Robotics Framework**
- ROS 2 Jazzy
- Cartographer
- RViz

**Image Processing and OCR**
- Tesseract OCR

**Speech Processing**
- PyAudio
- MFCC
- Voice Activity Detection (VAD)
- pyttsx3

**Hardware Components**
- Raspberry Pi 5 (4GB)
- RPLIDAR C1
- ESP32 Development Board
- USB Camera
- 25GA-370 DC Gear Motors with Encoders
- BTS7960 Motor Driver
- Bluetooth Speaker
- 12V Li-ion Battery Pack
- Chassis and Wheels

## 🔄 System Workflow

1. **Circular Upload:** The user uploads a circular document through the mobile application.
2. **Text Extraction:** Tesseract OCR extracts the textual content from the uploaded circular.
3. **Voice Interaction:** The user interacts with the robot using voice commands.
4. **Classroom Selection:** The user specifies the target classroom numbers.
5. **Mapping and Localization:** The robot uses SLAM-based mapping and localization to determine its position and navigate through the indoor environment.
6. **Obstacle Avoidance:** The robot detects obstacles and adjusts its navigation path.
7. **Classroom Navigation:** The robot reaches the designated classroom.
8. **Announcement Delivery:** The extracted circular content is converted into speech using pyttsx3 and delivered through the speaker.
9. **Repeat Option:** Listeners can request the announcement to be repeated.
10. **Task Completion:** The robot records the announcement status, sends a completion notification and returns to its docking station after completing the assigned classrooms.

## 📊 Project Results

- Implemented indoor mapping using RPLIDAR C1 and Raspberry Pi 5.
- Successfully mapped the indoor path from the cabin to two classrooms.
- Demonstrated partial environment mapping.
- Implemented SLAM-based localization and navigation visualization using RViz.

## 🚀 Future Enhancements

- Advanced 3D SLAM and intelligent navigation.
- Multilingual announcements using Natural Language Processing (NLP).
- Mobile application with live robot tracking and remote control.
- Cloud integration and centralized circular management.
- Full-campus navigation covering multiple blocks and floors.

## 💻 Project Domain

Robotics | Internet of Things (IoT) | Artificial Intelligence | Robots

## 👩‍💻 Contributors

Developed as a team academic project by:

- M. Yagna Sree
- A. Kavya Sri Harini
- M. Avanthi
- G. V. Gnana Karthik


---

**Note:** This repository documents the project architecture, implementation, source code and demonstration results. Features under future development are identified separately from implemented functionality.
