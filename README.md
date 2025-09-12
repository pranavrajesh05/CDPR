<!-- Banner -->
<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=YOUR_BANNER_IMAGE_ID" alt="CDPR Banner" width="80%">
</p>

# 📌 Cable-Driven Parallel Robot (CDPR)

## 📝 Project Overview

The **Cable-Driven Parallel Robot** is a 3-DOF robotic platform designed to move a suspended base using four stepper motors. The system is stabilized using feedback from an MPU6050 gyroscopic sensor. It supports both manual directional control via keyboard and automatic stabilization using passivity-based control (PBC). The platform has real-time feedback integration and separation of control logic for effective movement and correction.

- 📽️ [Project Presentation](https://drive.google.com/file/d/PRESENTATION_LINK/view)
- 📄 [Detailed Report (PDF)](https://drive.google.com/file/d/REPORT_LINK/view)

## 💻 Tech Stack

- **Microcontroller:** Arduino Uno
- **Motion Control:** NEMA 17 Stepper Motors, CNC Shield, A4988 Drivers
- **Sensors:** MPU6050 (IMU)
- **Programming Languages:** C++, Python
- **Communication:** Serial over USB, I2C, Wi-Fi (ESP8266 bridge)
- **Software Tools:** Arduino IDE, Python (for manual control), Real-time plotting (Matplotlib), Streamlit (for visualization - optional)
