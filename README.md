<div align="center">

# 👋 Hi there, I'm Nasim Sami

### 🤖 Robotics & Mechatronics Engineer | Reinforcement Learning & Autonomous Systems Researcher

[![GitHub Profile](https://img.shields.io/badge/GitHub-Nasim--Sami-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nasim-Sami)
[![Email](https://img.shields.io/badge/Email-nasimulsami752%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nasimulsami752@gmail.com)
[![Ubuntu](https://img.shields.io/badge/OS-Linux%20%7C%20Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)

<p align="center">
  <em>Passionate about building autonomous aerial & mobile robotics, real-time SLAM & navigation pipelines, constrained safe reinforcement learning, deterministic safety shields for LLM-driven flight, and cognitive adaptive systems.</em>
</p>

---

</div>

## 🛠️ Tech Stack & Expertise

### 🦾 Robotics & Autonomous Systems
<p>
  <img src="https://img.shields.io/badge/ROS_2-Jazzy%20%7C%20Humble-22314E?style=flat-square&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/PX4_Autopilot-v1.15_SITL-EE3322?style=flat-square&logo=drone&logoColor=white" />
  <img src="https://img.shields.io/badge/Simulation-Gazebo_Harmonic%20%7C%20RViz2-FF6600?style=flat-square&logo=gazebo&logoColor=white" />
  <img src="https://img.shields.io/badge/GCS-QGroundControl%20%7C%20MAVLink-007ACC?style=flat-square" />
  <img src="https://img.shields.io/badge/Navigation2-Active-28A745?style=flat-square&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/SLAM_Toolbox-Mapping-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/MoveIt_2-Motion_Planning-3B78E7?style=flat-square&logo=ros" />
  <img src="https://img.shields.io/badge/Robots-x500_Quadcopter%20%7C%20TurtleBot3%20%7C%20UR3-181717?style=flat-square" />
</p>

### 🧠 AI, Deep Learning & Autonomous Perception
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Safe_RL-PPO--Lagrangian%20%7C%20CMDP-FFD700?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/Computer_Vision-YOLOv8%20%7C%20OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Local_LLM-Ollama%20%7C%20Qwen_2.5-000000?style=flat-square&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Reinforcement_Learning-DQN%20%7C%20PPO%20%7C%20A2C-FFD700?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/AI_Vision-Google_MediaPipe-00C853?style=flat-square&logo=google" />
  <img src="https://img.shields.io/badge/LLM_Integration-Groq_API-F55036?style=flat-square" />
</p>

### 💻 Languages & Hardware
<p>
  <img src="https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Microcontrollers-ESP32%20%7C%20ESP8266%20%7C%20Arduino-E7352C?style=flat-square&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Full_Stack-Next.js%20%7C%20Prisma%20%7C%20Flask-000000?style=flat-square" />
</p>

---

## 🌟 Featured Repositories

### 🛡️ Safe Reinforcement Learning: [Safe-RL-Mobile-Robot-Navigation](https://github.com/Nasim-Sami/Safe-RL-Mobile-Robot-Navigation)
> **Constrained Deep Reinforcement Learning (CMDP) with PPO-Lagrangian on Continuous 360° LiDAR for Proven Zero-Collision Mobile Robot Navigation.**
>
> [![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
> [![ROS 2](https://img.shields.io/badge/ROS_2-Jazzy-22314E?style=flat-square&logo=ros&logoColor=white)](https://docs.ros.org/en/jazzy/)
> [![Gazebo](https://img.shields.io/badge/Gazebo-Harmonic-FF6600?style=flat-square&logo=gazebo&logoColor=white)](https://gazebosim.org/)
> [![Safe RL](https://img.shields.io/badge/CMDP-PPO--Lagrangian-FFD700?style=flat-square&logoColor=black)](https://github.com/Nasim-Sami/Safe-RL-Mobile-Robot-Navigation)
> [![Zero Collision](https://img.shields.io/badge/Collision_Rate-0.0%25_Verified-success?style=flat-square)](https://github.com/Nasim-Sami/Safe-RL-Mobile-Robot-Navigation)
>
> - **Pure End-to-End Safe RL:** Direct mapping from raw 360-degree LiDAR range beams and proprioceptive goal vectors to unicycle steering velocities without heuristic overrides or safety filters.
> - **Spatial 1D-CNN & Multimodal Fusion:** 3-stage 1D convolutional feature extractor capturing continuous angular free-space contours fused with target and velocity states.
> - **Twin Critics & Adaptive PID Lambda:** Decouples task reward value ($V^R$) from collision constraint risk ($V^C$) with PID-damped $\lambda \in [0, 5]$, eliminating freeze traps in tight corridors while guaranteeing $0.0\%$ collisions.

---

### 🚁 Autonomous Aerial Robotics: [Autonomous-Drone-PX4-ROS2-YOLO-LLM](https://github.com/Nasim-Sami/Autonomous-Drone-PX4-ROS2-YOLO-LLM)
> **Production-Grade Autonomous Aerial Robotics: Natural Language Mission Planning, Deterministic 3D Safety Gatekeeper, and Real-Time YOLOv8 Vision Perception.**
>
> [![ROS 2](https://img.shields.io/badge/ROS_2-Jazzy-22314E?style=flat-square&logo=ros&logoColor=white)](https://docs.ros.org/en/jazzy/)
> [![PX4 Autopilot](https://img.shields.io/badge/PX4-v1.15_SITL-EE3322?style=flat-square&logo=drone&logoColor=white)](https://px4.io/)
> [![Gazebo](https://img.shields.io/badge/Gazebo-Harmonic-FF6600?style=flat-square&logo=gazebo&logoColor=white)](https://gazebosim.org/)
> [![YOLOv8](https://img.shields.io/badge/Vision-YOLOv8_Nano-00FFFF?style=flat-square&logo=yolo&logoColor=black)](https://ultralytics.com/)
> [![Ollama](https://img.shields.io/badge/LLM-Qwen_2.5_1.5B-000000?style=flat-square&logo=ollama&logoColor=white)](https://ollama.ai/)
> [![QGroundControl](https://img.shields.io/badge/GCS-QGroundControl-007ACC?style=flat-square)](http://qgroundcontrol.com/)
> [![Demo Video](https://img.shields.io/badge/Demo_Video-1080p_60fps-blueviolet?style=flat-square&logo=youtube&logoColor=white)](https://github.com/Nasim-Sami/Autonomous-Drone-PX4-ROS2-YOLO-LLM/blob/main/Autonomous_Drone_PX4_ROS2_YOLO_LLM_Demo.mp4)
>
> - **Natural Language Mission Planning:** High-level mission extraction and waypoint decomposition (in English & Bengali) using an on-device Small Language Model (**Ollama `qwen2.5:1.5b`**).
> - **Deterministic 3D Safety Shield:** Prioritizing flight safety, a deterministic ROS 2 gatekeeper evaluates kinematic bounds, a $300\text{m}$ geofence, and 3D altitude overflight clearance to validate and bound LLM decisions before execution.
> - **Neural Vision Perception:** Ultralytics YOLOv8 Nano performing real-time obstacle proximity estimation and trigger-based aerial reconnaissance snapshots.
> - **Dual Telemetry Monitoring:** 10Hz MAVLink stream to **QGroundControl** (HUD, Artificial Horizon, Satellite Map) and an interactive **Web Ground Control Station**.

---

### 📂 All Repositories & Research Projects

| Project | Tech Stack | Highlights |
| :--- | :--- | :--- |
| 🛡️ [**Safe-RL-Mobile-Robot-Navigation**](https://github.com/Nasim-Sami/Safe-RL-Mobile-Robot-Navigation) | `PyTorch`, `PPO-Lagrangian`, `ROS 2 Jazzy`, `Gazebo Harmonic`, `TurtleBot3`, `1D-CNN` | Constrained Deep RL for mobile robot navigation on 360° LiDAR, featuring Twin Critics and adaptive PID $\lambda$ achieving 0.0% collisions across procedurally randomized domains. |
| 🚁 [**Autonomous-Drone-PX4-ROS2-YOLO-LLM**](https://github.com/Nasim-Sami/Autonomous-Drone-PX4-ROS2-YOLO-LLM) | `PX4 SITL`, `ROS 2 Jazzy`, `Gazebo Harmonic`, `YOLOv8`, `Ollama LLM`, `Micro-XRCE-DDS`, `QGC` | Autonomous quadcopter pipeline featuring bilingual voice/text mission planning, a deterministic 3D safety gatekeeper validating LLM commands, YOLOv8 vision, and 10Hz offboard trajectory tracking. |
| 🚀 [**ROS2-Mini-Projects**](https://github.com/Nasim-Sami/ROS2-Mini-Projects) | `ROS 2`, `Nav2`, `SLAM`, `MoveIt 2`, `Python` | Autonomous SLAM mapping, multi-waypoint patrol, SCARA MediaPipe hand teleop, and UR3 OMPL obstacle avoidance. |
| 🎓 [**Adaptive_MCQ_Real_Student_Session**](https://github.com/Nasim-Sami/Adaptive_MCQ_Real_Student_Session) | `PyTorch`, `RL (LSTM)`, `Groq LLM`, `Flask` | Intelligent tutoring system using Reinforcement Learning and Groq LLM for adaptive student learning sessions. |
| 🧠 [**Reinforcement-Learning-projects**](https://github.com/Nasim-Sami/Reinforcement-Learning-projects) | `PyTorch`, `Gymnasium`, `DQN`, `A2C` | Deep RL algorithms tested on CartPole-v1 and Atari Breakout benchmark environments. |
| 🦯 [**Blind_Stick_project**](https://github.com/Nasim-Sami/Blind_Stick_project) | `C++`, `ESP8266`, `Firebase`, `Android` | IoT assistive smart cane featuring ultrasonic obstacle alert, 3-stage fall detection, and real-time cloud sync. |
| 🚗 [**Car_parking_slot_management**](https://github.com/Nasim-Sami/Car_parking_slot_management) | `YOLOv8`, `CNN`, `OpenCV`, `ESP32-CAM` | Computer vision system for parking slot occupancy tracking and automated overparking encroachment detection. |
| 🎨 [**ExpressU**](https://github.com/Nasim-Sami/ExpressU) | `Next.js 15`, `TypeScript`, `Prisma`, `Tailwind` | Judgment-free creative expression platform engineered with intentional psychological safety architecture. |
| 🧪 [**Dynamic_student_simulator_lab**](https://github.com/Nasim-Sami/Dynamic_student_simulator_lab) | `Python`, `Flask`, `Stochastic Modeling` | Cognitive simulator modeling realistic student exam perception, pressure, and Elo-style dynamic learning. |

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Nasim-Sami&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nasim-Sami&layout=compact&theme=tokyonight&hide_border=true" height="165" />

</div>

---

## 📬 Connect With Me

- 📧 **Email:** [nasimulsami752@gmail.com](mailto:nasimulsami752@gmail.com)
- 🌐 **GitHub:** [@Nasim-Sami](https://github.com/Nasim-Sami)
- 🤝 Open to collaborations on **Robotics, Safe Reinforcement Learning, and Autonomous Systems Research**!
