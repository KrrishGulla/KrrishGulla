<h1 align="center">Krrish Gulla</h1>
<p align="center"><i>Building autonomous systems where GPS doesn't reach and latency doesn't wait.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Mechatronics_Engineering-Manipal_Institute_of_Technology-blue?style=for-the-badge" alt="MIT Manipal"/>
  <img src="https://img.shields.io/badge/Class_of-2027-lightgrey?style=for-the-badge" alt="Class of 2027"/>
</p>

---

## About Me

- Mechatronics Engineering student at Manipal Institute of Technology, working at the intersection of autonomous systems, embedded AI, and physical AI.
- Comfortable across the stack — from CAN-level firmware on flight controllers to LLM-based assistants running on edge hardware.
- Currently building GPS-denied navigation for autonomous drones, with hands-on work in sensor fusion, obstacle avoidance, and companion-computer integration.
- Author on two papers — one accepted at a conference (IoT ambulance telemetry), one IEEE (UAV precision landing) — with a patent in progress.

---

## Currently Building

### GPS-Denied Autonomous Drone Navigation — *Marut Dronetech (Internship)*

Building a full indoor navigation stack for a multirotor operating with no GPS and no external positioning system:

- **Simulation** — ArduPilot SITL on Gazebo Harmonic for pre-flight validation
- **State estimation** — EKF3 fused with millimeter-wave radar (NRA24 24GHz terrain, MR72 77GHz obstacle)
- **Obstacle avoidance** — BendyRuler-based avoidance in autonomous Guided mode
- **Compute** — Cube Orange+ flight controller paired with a Jetson Orin NX companion computer for higher-level processing

Also wrote the ArduPilot CAN rangefinder driver for JIYI Microbrain radar sensors from scratch — reverse-engineered the CAN frame protocol and implemented `AP_RangeFinder_JIYI_CAN` in C++.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

**GPS-Denied Drone Navigation**
Indoor autonomous navigation stack combining EKF3 state estimation, mmWave radar sensor fusion, and BendyRuler obstacle avoidance on ArduPilot.
`ArduPilot` `Gazebo Harmonic` `C++` `mmWave Radar`

</td>
<td width="50%" valign="top">

**RAG HR Policy Assistant**
Autonomous chatbot answering HR and policy queries via a RAG pipeline with semantic search, Azure OpenAI generation, and TTS delivery through a 3D avatar. Deployed as an internal tool.
`Python` `Azure OpenAI` `Semantic Search` `TTS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**IoT Ambulance Telemetry System**
Real-time ECG/SpO₂/GPS telemetry streamed from ambulances over LTE via MQTT to AWS IoT Core, with TLS 1.2/X.509 auth and SQLite edge caching for offline buffering. Conference paper accepted; patent in progress.
`STM32` `AWS IoT Core` `MQTT` `LTE`

</td>
<td width="50%" valign="top">

**UAV Precision Landing**
Vision-based autonomous landing combining deep learning for marker detection with image-based visual servoing for control. IEEE paper (team project).
`Webots` `MobileNetV2` `ResNet50` `ArUco` `IBVS`

</td>
</tr>
</table>

---

## Tech Stack

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![ArduPilot](https://img.shields.io/badge/ArduPilot-02569B?style=for-the-badge&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_IoT-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_OpenAI-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## Hardware

![Jetson Orin NX](https://img.shields.io/badge/Jetson_Orin_NX-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Cube Orange+](https://img.shields.io/badge/Cube_Orange+-orange?style=for-the-badge)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![RPLIDAR S2](https://img.shields.io/badge/RPLIDAR_S2-2C2C2C?style=for-the-badge)
![mmWave Radar](https://img.shields.io/badge/mmWave_Radar-4B0082?style=for-the-badge)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINK)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krrishgulla24@gmail.com)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KrrishGulla&show_icons=true&theme=tokyonight" alt="Krrish's GitHub Stats"/>
</p>
