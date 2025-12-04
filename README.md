# Blind-Sense-Real-time-object-detection-and-audio-assistance-for-visually-impaired.

# Blind Sense: Real-Time Object Detection & Audio Assistance

Blind Sense is an AI-powered assistive system designed to support visually impaired individuals by providing real-time object detection and audio feedback.  
The system uses an ESP32-CAM module along with the YOLO detection algorithm to recognize objects in indoor environments and announce them through speech.

---

## Overview

The solution enables users to understand their surroundings using voice commands.  
It detects objects, recognizes faces, reads text, assists in navigation, and supports an AI voice chatbot for interaction.

---

## Features

- Voice-controlled interface for hands-free operation
- Object detection in the camera feed
- Face recognition to identify known individuals
- Add new face to the system dynamically
- AI chat assistant for voice-based interaction
- Text recognition (OCR) to read printed text aloud
- Object search functionality within camera view
- Navigation assistance with directional output

## Project Structure

- **/datasets/** – Stores training and testing image data
- **/models/** – Contains trained YOLO and face recognition models
- **/utils/** – Utility functions and helper scripts
- **/hardware/** – ESP32 firmware and circuit diagrams
- **/images/** – Screenshots and result images for documentation

- **main.py** – Main entry point for voice-command processing
- **speech.py** – Handles speech-to-text and text-to-speech
- **object_detection.py** – Performs object detection using YOLO
- **face_recognition.py** – Face recognition utilities
- **faceregtest1.py** – Face recognition tester script
- **facesavetest1.py** – Save/register new face data
- **ai_assistant.py** – Voice-based AI chatbot module
- **navigate.py** – Basic navigation assistance
- **text_recognition.py** – OCR and reading text aloud
- **object_search.py** – Locate a specific object in the camera frame

- **requirements.txt** – Python dependency list


## Hardware Setup

![ESP32 and Arduino Connection](Sample/esp32_arduino_connection.png)

## Sample Output

![Sample Output](Sample/sample_output.png)
