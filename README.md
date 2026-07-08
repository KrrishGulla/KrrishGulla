# Krrish Gulla

Mechatronics Engineering student at Manipal Institute of Technology ('27). I work at the intersection of autonomous systems, embedded AI, and physical AI — from writing low-level firmware for flight controllers to deploying LLM-based assistants on edge hardware.

## What I'm building now

**GPS-Denied Autonomous Drone Navigation** · Marut Dronetech (Internship)

Building a full indoor navigation stack for a multirotor — no GPS, no external positioning. ArduPilot SITL on Gazebo Harmonic for simulation, EKF3 for state estimation using millimeter-wave radar (NRA24 24GHz terrain, MR72 77GHz obstacle), and BendyRuler-based obstacle avoidance in autonomous Guided mode. Running on Cube Orange+ flight controller with a Jetson Orin NX companion computer handling higher-level compute.

Also wrote the ArduPilot CAN rangefinder driver for JIYI Microbrain radar sensors from scratch — reverse-engineered the CAN frame protocol and implemented `AP_RangeFinder_JIYI_CAN` in C++.

## Selected projects

**RAG HR Policy Assistant** · Python, Azure OpenAI, semantic search, TTS
Autonomous chatbot that answers HR queries and company policy questions. Built a RAG pipeline with semantic search over policy documents — query comes in, relevant chunks are retrieved from the vector store, answer is generated via Azure OpenAI and delivered through a 3D avatar with TTS. Deployed as an internal tool.

**IoT Ambulance Telemetry System** · STM32, AWS IoT Core, MQTT, LTE
Real-time ECG/SpO₂/GPS telemetry streamed from ambulances to the cloud over LTE. TLS 1.2/X.509 auth, SQLite edge caching for offline buffering, MQTT over AWS IoT Core. Conference paper accepted for publication. Patent in progress.

**UAV Precision Landing** · Webots, MobileNetV2, ResNet50, ArUco, IBVS
Vision-based autonomous landing using deep learning for marker detection and image-based visual servoing for control. IEEE paper (team project).

**Heat Transfer ML Pipeline** · Python, XGBoost, Random Forest, SHAP, Optuna
End-to-end ML pipeline for heat transfer coefficient prediction with hyperparameter tuning via Optuna and feature attribution via SHAP analysis.

## Hardware & stack

**Edge AI** · Jetson Orin NX, Cube Orange+, STM32, Siemens S7-1200 PLC
**Sensors** · RPLIDAR S2, NRA24 nanoradar, MR72 nanoradar, DroneCAN proximity radar
**Firmware/Middleware** · ArduPilot, MAVLink v2, CAN, DroneCAN, UART, ROS 2
**Software** · C++, Python, Gazebo Harmonic, AWS IoT Core, Azure OpenAI, MQTT

## Where I'm headed

Robotics and autonomous systems — specifically perception, navigation, and edge inference. Target roles at companies building physical AI infrastructure: Nvidia, Edge Cortix, and similar.

---
📫 [LinkedIn](https://linkedin.com/in/YOUR_LINK) · krrishgulla24@gmail.com
