# 🤖 Johnny Humanoid Robot (Showcase)

> **Note:** The source code for this project is private. This repository outlines the architecture, hardware integration, and AI logic utilized in the development of Johnny.

## 📌 Project Overview
**Johnny** is an AI-driven, 3D-printed humanoid robot based on the INMOOV architecture. Developed between Nov 2023 and Sep 2024, the goal of this project was to synchronize cloud-based language models with physical hardware, enabling the robot to generate autonomous motor commands during real-time conversations.

<p align="center">
  <img src="assets/johnny_speaking.gif" width="600" alt="Johnny Robot Speaking">
</p>

## 🛠️ System Architecture

### AI & Cognitive Processing
* **Core LLM:** Google Vertex AI (chat-bison) utilized for rapid, context-aware conversational responses.
* **Speech Pipelines:** Integrated robust cloud-based STT/TTS services for seamless voice interaction.

### Hardware & Control Systems
* **Microcontroller:** Arduino ecosystems driving the physical movements.
* **Hardware Assembly:** Integrated and assembled complex 3D-printed mechanical components, routing power and signal lines for multiple servos.
* **Computer Vision:** Camera and sensor integration to support advanced physical interactions and object awareness.

## 💡 Key Achievements
* Successfully translated abstract text/AI output into precise, real-time physical servo commands.
* Optimized the data flow between Python backend scripts and Arduino microcontrollers via serial communication.

---
*For technical inquiries or detailed discussions regarding the architecture, feel free to contact me.*
