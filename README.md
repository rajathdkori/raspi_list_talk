# Raspberry Pi Publisher–Subscriber Communication

A ROS 2 package developed for implementing **publisher–subscriber communication** on a **Raspberry Pi** using **ROS 2 Jazzy** and **Ubuntu 24.04**. This project demonstrates the fundamentals of ROS 2 node communication and serves as a foundation for robotics and embedded system applications.

## Features

* ROS 2 publisher and subscriber nodes
* Inter-node communication using ROS 2 topics
* Python-based implementation (`rclpy`)
* Lightweight and modular package structure
* Optimized for Raspberry Pi 4
* Easy integration with sensors and actuators

## Prerequisites

* Ubuntu 24.04 LTS
* ROS 2 Jazzy
* Python 3
* Colcon Build Tools

## Installation

```bash
cd ~/ros2_ws/src
git clone https://github.com/rajathdkori/raspi_list_talk.git

cd ~/ros2_ws
colcon build
source install/setup.bash
```

## Usage

Run the publisher:

```bash
ros2 run raspi_list_talk talker
```

Run the subscriber:

```bash
ros2 run raspi_list_talk listener
```

## Applications

* ROS 2 communication fundamentals
* Raspberry Pi robotics
* Sensor and actuator interfacing
* Distributed robotic systems
* Educational ROS 2 projects

## Author

**Rajath D Kori**

GitHub: https://github.com/rajathdkori
