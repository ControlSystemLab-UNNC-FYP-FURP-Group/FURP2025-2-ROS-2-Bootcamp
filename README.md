# 🤖 FURP: ROS 2 Bootcamp (Humble)

**Faculty of Science and Engineering Undergraduate Research Project**  
*Master Next-Gen Robotics Development with ROS 2*

[![ROS2](https://img.shields.io/badge/ROS2-Humble-Hawksbill-blue?logo=ros)](https://docs.ros.org/en/humble/)
[![Gazebo](https://img.shields.io/badge/Gazebo_Fortress-ROS2-FF3000?logo=gnu)](https://gazebosim.org/home)

## 🚀 Overview
This modern bootcamp introduces **ROS 2 Humble Hawksbill** - the newest LTS version of the Robot Operating System. Through hands-on projects, you'll master ROS 2's enhanced DDS communication, real-time capabilities, and production-grade tooling. Progress from core concepts to deploying **microservice-style robotic systems** with cloud-native integration.

🚀 *Why ROS 2?* Designed for industrial applications with enhanced security, multi-robot support, and real-time performance. Used in NASA's Gateway lunar station and BMW's autonomous fleets.

## ✨ Core Curriculum
- **ROS 2 Architecture**: Nodes, lifecycle, parameters, and QoS configurations
- **Next-Gen Toolchain**: `colcon`, `ros2cli`, Launch Files, and `rqt` evolution
- **Cloud Robotics**: Integrate ROS 2 with Kubernetes and AWS RoboMaker
- **Security Essentials**: ROS 2 security enclaves and DDS-Security

## 🎯 Learning Outcomes
1. ✅ Migrate ROS 1 concepts to ROS 2 Humble
2. 🔍 Implement real-time controls with ROS 2 TSC (Timing-Compatible System) 
3. 🛠️ Containerize robotic applications using Docker + ROS 2
4. 📊 Build ROS 2-Web interfaces with Foxglove Studio

## 🧰 Tech Ecosystem
| Category       | Tools                                                                                     |
|----------------|------------------------------------------------------------------------------------------|
| **ROS 2 Stack**| Humble Hawksbill, Ubuntu 22.04, Python 3.10, C++17                                       |
| **Simulation** | Gazebo Fortress, TurtleBot4, Husky UGV (ROS 2 port)                                      |
| **Middleware** | Micro-ROS (for embedded), Cyclone DDS, rosbag2                                           |
| **Tools**      | VS Code + ROS 2 Extension, SROS2 security tools, Colcon                                  |

## 👩💻 Student Journey
### Prerequisites
- Basic **Python**/C++ skills (OOP concepts)
- Linux terminal familiarity (`bash`, `ssh`) 
- Excitement for deployable robotics! 🚀




# Workloads
## 1. **Week 1**: Install an Ubuntu 2204 virtual machine and follow the instructions on ros.org to install ros humble. Try the play with ros2 tutorial, DDL: March 11th, office hour/meeting, Match 12th 4pm

## 2. **Week 2**: Setup the machine, Mini PC Setup Guide 🚀


### Overview
- **Mini PC for ROS Bootcamp**  
- **CPU:** Intel N100  
- **Note:** This mini PC does not include built-in WiFi 📡.

### Connecting to Your Computer 💻
- **Hardware Setup:**  
  - Connect an HDMI cable from the mini PC to an HDMI capture card.  
  - Plug the HDMI capture card into your laptop or desktop.
- **Viewing the Device Screen:**  
  - Open your computer's camera application and switch the camera source to view the device's screen.
- **Peripheral Setup:**  
  - The mini PC requires a separate keyboard and mouse to be used.
- **Remote Access Recommendation:**  
  - After the initial configuration, it is recommended to install remote access software like **ToDesk** or **NoMachine** for easier remote connection.

### Installation Requirements
1. **Operating System:**  
   - Install **Ubuntu 22.04 Desktop**.  
   - [Download Ubuntu 22.04](#) *(https://releases.ubuntu.com/jammy/)*

2. **ROS 2 Humble:**  
   - Install **ROS 2 Humble**.  
   - [Download ROS 2 Humble](#) *(https://docs.ros.org/en/humble/Installation.html)*

### Network Configuration 📱
- Since the mini PC lacks WiFi, you will need to share your phone's internet connection via USB tethering.
- **Recommendation:**  
  - Connect your phone to **eduroam**.
  - Then, use USB tethering to provide internet access to the mini PC.

### Next Steps
- Once the installation is complete, please come find me to collect your LiDAR sensor 🔧.

Happy bootcamping and enjoy your new setup! 🎉


```text
📖 Core Resources:
- ROS 2 Humble Documentation: [https://docs.ros.org/en/humble/](https://docs.ros.org/en/humble/Installation.html)
- The ROS 2 Developer's Guide: [https://www.packtpub.com/ros2-book ](https://docs.ros.org/en/humble/Tutorials.html)
