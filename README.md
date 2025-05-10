# An-Intelligent-IoT-Based-Crop-Protection-System-with-AI-Driven-Animal-Detection-and-Water-Management
Developed an AI-powered agricultural surveillance system using Raspberry Pi 5 and YOLOv8 to detect crop-destroying animals in real-time. The system uses deterrent sounds, monitors environmental conditions, and sends alerts via the Blynk IoT app. It enables remote farm management and supports precision agriculture with scalable, low-cost solutions.
## Features

- **Animal Detection**: Real-time detection of animals like birds, monkeys, and wild boars using YOLOv8.
- **Deterrent Sounds**: Plays animal-specific deterrent sounds (e.g., bird sound, monkey sound) upon detection.
- **Blynk App Integration**: Sends real-time alerts and allows remote control of the system (e.g., controlling motors, buzzers, or LEDs).
- **Environmental Monitoring**: Monitors water levels, rain detection, and environmental conditions in the field.
- **Real-Time Data Display**: Displays real-time animal detection data, notifications, and control features in the Blynk app.
- **Integration with Raspberry Pi**: Uses Raspberry Pi 5 for both detection and control, integrating GPIO pins, sensors, and the camera module.

## System Architecture

The system architecture consists of the following components:
- **YOLOv8 Model**: Trained to detect animals like birds, monkeys, and wild boars.
- **Raspberry Pi 5**: Handles the image capture, animal detection, and control logic.
- **Camera Module**: Captures real-time video for detection.
- **Blynk App**: A mobile app to receive alerts, view status, and control system components.
- **Environmental Sensors**: Includes water level sensors and rain sensors to provide real-time environmental data.

## Prerequisites

Before you begin, make sure you have the following:

- **Hardware**:
  - Raspberry Pi 5 (8GB version recommended)
  - Camera Module for Raspberry Pi
  - Buzzer, Servo Motors, LEDs for control
  - Water Level Sensor
  - Rain Sensor
  - Blynk-supported device (smartphone)

- **Software**:
  - Python 3.x
  - OpenCV
  - PyTorch (for YOLOv8)
  - Blynk Library for Python
  - Twilio (for SMS and WhatsApp notifications)
  - Raspberry Pi GPIO Library
  - Additional Python packages listed in `requirements.txt`
