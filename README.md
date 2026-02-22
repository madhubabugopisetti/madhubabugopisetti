# Madhu Babu Gopisetti - Robotics & Full-Stack Software Engineer

## 👨‍💻 About Me:
I am a passionate **Robotics Software Engineer** and **Full-Stack Engineer** with 4+ years of experience building production-grade systems in regulated, high-reliability environments. I specialize in autonomous mobile robots, robotic manipulators, multi-robot systems using ROS2, and end-to-end software development across frontend, backend, and AI/ML domains.

## 📫 Contact Information:
- 📞 Phone: +91 7981960932
- 📧 Email: madhubabugopisetti27@gmail.com
- 💼 LinkedIn: [madhubabu-gopisetti](https://linkedin.com/in/madhu-g-6524153b2/)
- 🐙 GitHub: [madhubabu-gopisetti](https://github.com/madhubabu-gopisetti)

## ⚡ Fun Fact:
Why do robotics engineers make great programmers? **Because they're used to handling exceptions in the real world.**

---

## 💼 Work Experience

### **Full-Stack Software Engineer**
**DBS Tech India, Hyderabad** | *July 2022 – Present*

**Project: SDWT**
- Stepped into undocumented legacy systems without KT, reverse-engineered architectures, and delivered reliable production enhancements independently.
- Owned and upgraded multiple production-critical enterprise systems, executing major version migrations across **8+ React**, **4 Angular**, and **3 Node** applications.
- Designed and maintained **Node.js** backend services and integration layers, improving API reliability and data flow consistency across distributed internal platforms.
- Contributed to **20+ internal banking systems** while ensuring compliance, stability, and seamless cross-system integration.
- Reviewed **300+ PRs**, resolved **150+ defects**, and executed **10+ CRs** while maintaining **96% uptime** during releases.
- Implemented automation, scripting, and RPA workflows (including Python-based tooling) to eliminate repetitive operational tasks.

**Project: UPI**
- Worked on a high-availability **UPI payments platform** handling real-time financial transactions in a regulated banking environment.
- Served as the sole developer for key modules — owning end-to-end delivery including design, development, automated testing, CI/CD pipelines, and production support.
- Designed and maintained **Node.js** services connecting internal banking systems, NPCI interfaces, and downstream services.
- Implemented validations, error handling, audit logging, and monitoring to ensure transactional integrity and regulatory compliance.

**Project: TMOP**
- Worked on a modular Angular-based platform allowing banking teams to onboard and operate independent widgets within a centralized system.
- Delivered and productionized four banking widgets: **Counterparty Widget**, **SSI Widget**, **Dashboard Widget**, and **ANN/DSB Widget**.

---

## 🚀 Projects

### 🤖 Autonomous Mobile Robot — NEXUS Series

**[NEXUS-AMR (Keyboard Control)](https://github.com/madhubabu-gopisetti)**
- Built a differential-drive mobile robot in **ROS2 Jazzy** and **Gazebo** using URDF/XACRO.
- Implemented **SLAM** using slam_toolbox, **AMCL** for localization, and the full **Nav2** navigation stack.
- Result: A complete classical autonomous navigation stack — drive, map, localize, and navigate to goals reliably.

**[NEXUS-ADS (OpenCV Automated)](https://github.com/madhubabu-gopisetti)**
- Extended NEXUS-AMR with camera and LiDAR sensors and **OpenCV-based perception nodes** for docking target detection.
- Built autonomous control nodes to convert vision output into motion commands — no keyboard required.

**[NEXUS-ADS-INTEL (ML Automated)](https://github.com/madhubabu-gopisetti)**
- Replaced rule-based vision with **YOLO** object detection and **LiDAR feature extraction**.
- Integrated **sensor fusion** (Camera + LiDAR) and trained **Logistic Regression** and **Random Forest** models for autonomous navigation decisions.
- Built dataset collection, training, and real-time inference pipelines fully inside ROS2.

**[ROBOT: Real Hardware Implementation](https://github.com/madhubabu-gopisetti)**
- Assembled a real differential-drive robot using **Raspberry Pi 5** and **RP2040 MCU**.
- Designed full power and motor control stack (BTS7960 drivers, GB37 encoded motors), integrated **YDLIDAR G2**, and deployed full SLAM + Nav2 stack on physical hardware.

---

### 🦾 Autonomous Grasping System — NEXUS Manipulator Series

**[NEXUS-MM (Keyboard Control)](https://github.com/madhubabu-gopisetti)**
- Built a **6-DOF robotic arm** in ROS2 using URDF/XACRO and integrated with **ros2_control** for joint-level control in Gazebo and RViz.

**[NEXUS-AGS (OpenCV Automated)](https://github.com/madhubabu-gopisetti)**
- Added wrist-mounted camera and built a **visual servoing pipeline** for object detection, centroid extraction, and closed-loop end-effector alignment.

**[NEXUS-AGS-INTEL (ML Automated)](https://github.com/madhubabu-gopisetti)**
- Integrated **YOLO-based perception** for object detection/classification and built a full ML pipeline inside ROS2 for dynamic grasp behavior.

---

### 🕷️ Legged Robot — NEXUS Spider

**[NEXUS SPIDER (Simulation)](https://github.com/madhubabu-gopisetti)**
- Designed the full spider robot in **Blender**, built URDF/XACRO model, and implemented gait scripts in ROS2 + Gazebo for stable standing and walking.

**SPIDER ROBOT: Real Hardware**
- Built a real multi-legged robot using **SG90 servos**, **PCA9685 PWM controller**, and **ESP8266 MCU**.
- Implemented servo calibration, joint zeroing, and motion sequencing for coordinated gait control.

---

### 🚀 NEXUS FLEET — Full Mobile Manipulation System

**[(Simulation-Based Autonomous Mobile Manipulation)](https://github.com/madhubabu-gopisetti)**
- Integrated NEXUS-ADS and NEXUS-AGS into a single coordinated ROS2 platform using **Nav2** for mobile base autonomy and **ros2_control** for manipulator control.
- Full mission pipeline: *navigate → align → deploy arm → pick object → navigate → place object.*

---

## 🧰 Technologies & Tools

### 🤖 Robotics:
<p align="left">
  <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS2"/>
  <img src="https://img.shields.io/badge/ROS1-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS1"/>
  <img src="https://img.shields.io/badge/Gazebo-orange?style=for-the-badge" alt="Gazebo"/>
  <img src="https://img.shields.io/badge/MoveIt-blue?style=for-the-badge" alt="MoveIt"/>
  <img src="https://img.shields.io/badge/Nav2-green?style=for-the-badge" alt="Nav2"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white" alt="Blender"/>
</p>

### 💻 Programming:
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cpp" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/>
</p>

### 🌐 Frontend:
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original.svg" alt="angular" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="nextjs" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" alt="vuejs" width="40" height="40"/>
</p>

### ⚙️ Backend & DevOps:
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" alt="jenkins" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
</p>

### 🧠 AI / Machine Learning:
<p align="left">
  <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/>
  &nbsp;&nbsp;
  <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge" alt="YOLO"/>
</p>

---

## 🎓 Education

**B.Tech** — Vishnu Institute of Technology | *2018 – 2022*
