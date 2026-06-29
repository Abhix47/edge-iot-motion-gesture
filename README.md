# Edge IoT Motion Gesture Recognition

**Government College of Engineering Kannur (GCEK) – Edge IoT Internship Assignment**

---

## Overview

This project demonstrates a real-time motion gesture recognition system built using an **ESP32**, **MPU6050 Accelerometer**, **Edge Impulse TinyML**, and a **Firebase-hosted web application**. Motion data is captured from the accelerometer, processed locally on the ESP32 using an Edge Impulse machine learning model, and displayed through a responsive web dashboard.

---

## Features

* Real-time motion gesture recognition
* ESP32 embedded implementation
* MPU6050 accelerometer integration
* Edge Impulse TinyML inference
* Firebase-hosted web dashboard
* Responsive user interface
* Live dashboard displaying:

  * Current gesture
  * Prediction confidence
  * Last updated time
  * Connection status
  * Recent prediction history

---

## Technologies Used

### Hardware

* ESP32 Development Board
* MPU6050 Accelerometer
* USB Cable

### Software

* Edge Impulse
* PlatformIO
* Arduino Framework
* Firebase Hosting
* HTML
* CSS
* JavaScript
* Visual Studio Code
* Git & GitHub

---

## Project Structure

```text
edge-iot-motion-gesture/
│
├── Motion_Gesture_AI/
│   └── ESP32 firmware and Edge Impulse model
│
├── Motion_Gesture_WebApp/
│   └── Firebase-hosted web application
│
├── images/
│   └── dashboard.png
│
├── docs/
│
└── README.md
```

---

## Workflow

1. Read motion data from the MPU6050 sensor.
2. Preprocess the sensor values.
3. Run inference using the Edge Impulse model.
4. Classify the performed gesture.
5. Display the prediction on the web dashboard.

---

## Web Application

The project includes a responsive Firebase-hosted dashboard for monitoring motion gesture predictions in real time.

### Live Demo

🔗 https://edge-iot-motion-gesture.web.app/

---

## Project Screenshot

![Motion Gesture Dashboard](images/dashboard.png)

---

## GitHub Repository

🔗 https://github.com/Abhix47/edge-iot-motion-gesture

---

## Project Status

**Completed** ✅

---

## Author

**Abhijith Sathyan**

Artificial Intelligence & Machine Learning Student

---

## Internship

**Government College of Engineering Kannur (GCEK)**

Edge IoT Internship Assignment
