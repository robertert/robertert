<div align="center">

# Hi, I'm Robert 👋

### Software Developer | Data Visualization, Embedded & Robotics

*I build software that touches the physical world: dashboards on live data, Linux machines in the field, and robots.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/robert-jacak-303270332/)
[![Email](https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail)](mailto:jacakrobert33@gmail.com)

</div>

---

## About me

- 📊 **Frontend Developer at [Black Label](https://blacklabel.net/)**, a data visualization software house. I build interactive dashboards and map-based tools in React, TypeScript and Highcharts, plus the Python and Node.js services behind them.
- 🥊 **Developer of CardioBoxer**, a commercial fleet of boxing fitness machines running embedded Linux, with remote OTA updates and monitoring.
- 🌱 **Building an autonomous solar-powered robot** as my engineering thesis at AGH University of Krakow (Computer Science and Intelligent Systems, graduating 01.2027).

---

## Tech stack

| Area | Technologies |
| :--- | :--- |
| **Frontend & dataviz** | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Highcharts](https://img.shields.io/badge/Highcharts-8087E8?style=flat-square) ![MapLibre GL](https://img.shields.io/badge/MapLibre_GL-396CB2?style=flat-square&logo=maplibre&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **Embedded & robotics** | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![ESP32 (ESP-IDF)](https://img.shields.io/badge/ESP32_(ESP--IDF)-E7352C?style=flat-square&logo=espressif&logoColor=white) ![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4CAF50?style=flat-square) ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![I²C / UART](https://img.shields.io/badge/I²C_/_UART-555555?style=flat-square) ![MQTT](https://img.shields.io/badge/MQTT-3C5280?style=flat-square&logo=mqtt&logoColor=white) ![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white) ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white) |
| **Linux & DevOps** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Fly.io](https://img.shields.io/badge/Fly.io-24175B?style=flat-square&logo=flydotio&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

---

## Featured projects

### 🥊 CardioBoxer ![Commercial](https://img.shields.io/badge/COMMERCIAL-FF6F00?style=flat-square)

A complete hardware-software platform for boxing fitness machines, live on 20+ machines. Built in a two-person team.

<details>
<summary>Click to see demo</summary>
<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/908d1657-d2fc-4705-932b-653c498e306b" width="50%" alt="CardioBoxer Demo" />
</div>
<br>
</details>

- **Kiosk software:** an Electron + React app on embedded Linux, with Python system services that read punch pads over I²C or UART and drive LEDs and audio.
- **Fleet management:** signed OTA updates with automatic rollback, remote access, and centralized logs and metrics with automated anomaly detection.
- **Cloud:** Supabase backend shared with a mobile app, with live leaderboards and Stripe subscriptions for machine operators.

**Tech:** `Electron` `React` `Python` `Linux` `SQLite` `Supabase` `Stripe`

---

### 🌱 [Flora](https://github.com/robertert/FloraV2) ![Thesis](https://img.shields.io/badge/ENGINEERING_THESIS-2E7D32?style=flat-square)

An autonomous solar-powered robot that drives across a lawn following the sun, monitors soil and weather, and waters its plant.

- **Firmware:** written in C for two ESP32-S3 units (drive base and sensor mast) linked over UART.
- **Navigation:** wheel odometry, IMU and compass fused in a Kalman filter, with PID drive control and sonar obstacle detection.
- **Connectivity:** OTA updates and telemetry over MQTT to a Grafana dashboard, plus a web panel for remote control.
- **Hardware:** my own PCBs (KiCad) and 3D-printed body.
- **Quality:** core algorithms are unit-tested on a PC and run in CI.

**Tech:** `C` `ESP-IDF` `FreeRTOS` `ESP32-S3` `MQTT` `KiCad` `Docker`

<details>
<summary>First generation: FloraSense</summary>
<br>

The earlier version of the robot: an ESP32 light-following robot that docks with a BLE-connected watering station, with a FastAPI + MQTT backend, a React Native app and a web dashboard.

[Robot firmware](https://github.com/robertert/FloraSense) | [Dock firmware](https://github.com/robertert/FloraSense/tree/station) | [Server](https://github.com/robertert/FloraSenseServer) | [Web dashboard](https://github.com/robertert/FloraWeb)

| Hardware demo | Mobile | Mobile | Mobile | Mobile |
| :---: | :---: | :---: | :---: | :---: |
| ![Demo](https://github.com/user-attachments/assets/c4a06b6d-79cb-47eb-972c-2267190cce1c) | ![1](https://github.com/user-attachments/assets/0f903328-6b59-484a-a540-8934efe2b4dd) | ![2](https://github.com/user-attachments/assets/e67cbf81-6ab8-4262-95c7-52313d7657d5) | ![3](https://github.com/user-attachments/assets/54eda29a-ea65-4271-ac84-b4a845015f78) | ![4](https://github.com/user-attachments/assets/a6da4ee9-a2a3-4c30-8c8b-dde3d68ff972) |

</details>

---

### 📊 Data visualization at Black Label ![Commercial](https://img.shields.io/badge/COMMERCIAL-FF6F00?style=flat-square)

Client-facing dashboards and tools built with React, TypeScript and Highcharts. The code is private, but some highlights:

- **Route planner:** a platform scheduling field installation crews across Poland, with a Python optimizer (OR-Tools, real driving times from OSRM) that plans 180 jobs for 6 crews in about 13 s.
- **Live vessel map:** around 3,500 ships on real AIS data, rendered live with MapLibre GL and Highcharts.
- **Talk to Data:** an LLM agent that answers questions by driving the charts in the UI.
- **Explainable AI dashboard:** shows which words drive each prediction of a fine-tuned text classifier.

**Tech:** `React` `TypeScript` `Highcharts` `MapLibre GL` `Next.js` `FastAPI` `Fastify`

---

### 🥑 [Memvocado](https://github.com/robertert/memvonadoapp)

A flashcard app that pairs the FSRS spaced-repetition algorithm with gamification: streaks, leagues and a growing avocado mascot.

<details>
<summary>Click to see demo</summary>
<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/71df2e98-890c-4d01-827a-c2f8049677d1" width="50%" alt="Memvocado Demo" />
</div>
<br>
</details>

- Gesture-driven reviews with fluid animations.
- Decks created by camera OCR scan or AI extraction from PDF/DOCX files.
- An in-app AI tutor that explains answers and generates mnemonics.

**Tech:** `React Native (Expo)` `TypeScript` `Firebase` `Reanimated` `Jest`

---

## More projects

| Project | What it is | Tech |
| :--- | :--- | :--- |
| **Email2SMS** (commercial) | Android app forwarding emails as SMS around the clock, ~300 messages per hour | React Native, Kotlin native module, Firebase |
| **BoxerCardio Mobile** (commercial) | First companion app for CardioBoxer: leaderboards, groups, achievements | React Native, Firebase |
| [**Pseudo Interpreter**](https://github.com/MaciejJamrozy/projectPseudo) | Interpreter for a custom strongly typed language with its own call stack | Python, ANTLR4 |
| [**TeamtailorExport**](https://github.com/robertert/TeamtailorExport) | CSV export service streaming large datasets with backpressure | Node.js, TypeScript, Docker |
| [**PommermanRL**](https://github.com/robertert/PommermanRL) | Reinforcement learning agents for a Bomberman-style game | Python, PyTorch, Stable Baselines 3 |
| [**AirportTaxiSimulation**](https://github.com/robertert/AirportTaxiSimulation) | Agent-based simulation of aircraft and vehicles on an airport apron | Python, MESA |

---

## Contact

💼 [LinkedIn](https://www.linkedin.com/in/robert-jacak-303270332/) · ✉️ [Email](mailto:jacakrobert33@gmail.com)
