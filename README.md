# Attendance-Marking-System

## 📌 Overview
This project is a Raspberry Pi Zero 2W-based Smart Attendance System that combines facial recognition and RFID authentication for secure and automated attendance marking.

The system was developed as an early-stage prototype before transitioning to a more advanced architecture.

---

## 🎯 Objective
To build a low-cost, embedded attendance solution capable of:
- Face-based identification
- RFID-based registration and verification
- Ethernet-based data communication
- Local training and database management

---

## 🧠 Core Features

- 📷 Face Recognition using USB Webcam
- 🪪 RFID-based User Registration
- 🗂️ On-device Face Data Collection & Model Training
- 🌐 Ethernet Communication for Data Transfer
- 📝 Automated Attendance Logging
- 🔐 Reduced Proxy Attendance Risk

---

## 🏗️ Hardware Components

- Raspberry Pi Zero 2W  
- USB Webcam  
- RFID Reader Module  
- Ethernet Adapter  
- Power Supply Unit  

---

## 💻 Software Stack

- Python  
- OpenCV  
- Face Recognition Library  
- Socket Programming (LAN Communication)  
- CSV / Local Database Storage  

---

## ⚙️ System Workflow

1. **User Registration**
   - RFID card is scanned.
   - Face images are captured using webcam.
   - Images are stored and used for training.

2. **Model Training**
   - Face dataset is processed.
   - Encodings are generated and stored.

3. **Attendance Marking**
   - User scans RFID.
   - Face verification is performed.
   - If matched, attendance is logged and optionally sent over LAN.

---


## 📊 Limitations (Prototype Stage)

- Limited processing power (Pi Zero 2W constraints)
- Basic spoof detection
- Dependent on lighting conditions
- No advanced liveness detection

---

## 🔮 Future Improvements

- Server-based processing
- IR-based anti-spoof detection
- Cloud dashboard integration
- Centralized database system

---

## 👥 Developed By

Engineering Team – IoT & Embedded Systems  
Lovely Professional University  

---

## 📜 License
For academic and research use only.
