# 🤖 Johnny Humanoid Robot — AI & Embedded Integration Showcase

<p align="center">
  <img src="media/johnny_demo.gif" width="400" alt="Johnny Robot Demo" />
</p>

> **Note:** The source code for this project is private. This repository documents the hardware integration, serial synchronization, and cloud AI architecture.

## 📌 Project Overview
**Johnny** is an AI-driven, 3D-printed humanoid robot built on the INMOOV mechanical platform. The project focused on synchronizing cloud-based generative language models with Arduino microcontrollers to generate speech-synchronized physical gestures in real-time.

---

## 🏗️ Hardware-to-Cloud Pipeline
The interaction loop is designed to be seamless and responsive. The onboard microphone and camera array capture the user's spoken queries, which a Python-based core architecture packages and sends to **Google Vertex AI** (chat-bison).

---

## 🛠️ Cloud-to-Hardware Synchronization
Translating text tokens into physical movement required precise orchestration:

* **Audio Output:** The Python core processes the Vertex AI text through a TTS engine and outputs spoken audio to the user.
* **Motion Synchronization (UART):** Simultaneously, the Python core translates the response intent into serial command packets and sends them to the Arduino microcontroller.
* **Actuation:** The Arduino translates the serial commands into coordinated PWM signals, driving the servo actuators for real-time physical gestures.

<p align="center">
  <img src="media/johnny_front.jpg" width="48%" alt="Johnny Front View" />
  &nbsp;
  <img src="media/johnny_arduino.jpg" width="48%" alt="Arduino Setup & Wiring" />
</p>

---

## ⚙️ Mechanical & Sensor Integration
Building Johnny required extensive hands-on hardware engineering. I integrated, wired, and calibrated 3D-printed mechanical components, servo horns, and linkages, alongside positioning camera inputs to support visual awareness triggers during conversations.

<p align="center">
  <img src="media/johnny_assembly.jpg" width="600" alt="Johnny Mechanical Assembly" />
</p>

---

## 📬 Contact
* **Email:** [omerfaruk.kus@outlook.com](mailto:omerfaruk.kus@outlook.com)
* **LinkedIn:** [linkedin.com/in/omrfrkkus](https://linkedin.com/in/omrfrkkus)
