# Electrical Systems Integration Project
# 电子信息机器人ROS Jetson Nano 集成视觉项目

## Project Overview

### Part 1: Mastering Basic Linux Commands and AEV Components

The first part of the project involved mastering basic Linux commands and the operation of electronic speed controllers and autonomous electric vehicle (AEV) components.

- **Linux Commands:**
  - Mastered necessary Linux commands to program the Jetson Nano.

- **Device Management:**
  - Set up udev rules to manage device permissions for components such as VESC, lidar, and cameras on the Jetson Nano.

- **VESC Software:**
  - Installed and configured VESC software.
  - Ensured proper motor operation and set safety parameters.
  - Used VESC tools for real-time data analysis.

### Part 2: Integrating AEV Components and Setting Up Simulation

The second part of the project focused on integrating various AEV components into the ROS system and setting up a simulation environment.

- **ROS Integration:**
  - Integrated AEV components into the ROS system.

- **Simulation Environment:**
  - Set up a simulation environment using the F1tenth simulator for pre-experimental testing.

- **Manual Control and Data Analysis:**
  - Controlled the AEV manually using a joystick.
  - Adjusted the vehicle odometer.
  - Conducted experiments using data from sensors such as lidar and cameras integrated into the AEV system.

### Bonus computer vision

- **Camera Integration:**
  - Demonstrated successful integration of the camera by showcasing the EV's ability to detect and respond to a person using the captured data.
  - The workflow diagram depicted the detection process, which relied on the DNN (Deep Neural Network) Inference Library.

- **Detection Algorithm:**
  - Implemented a topic called "detect_person/confidence" to publish a confidence node based on Linux Operation, allowing selective response to only a person in front of the EV.

- **Navigation Algorithm:**
  - Created a new AEV navigation algorithm that utilized the publish and subscribe principle in ROS (Robot Operating System).

### Outcomes

- Achieved a comprehensive understanding and practical application of system integration and data processing in an autonomous vehicle environment.

---

## 项目概述

### 第1部分：掌握基本的Linux命令和AEV组件

项目的第一部分涉及掌握基本的Linux命令以及电子速度控制器和自主电动车（AEV）组件的操作。

- **Linux命令：**
  - 掌握了编程Jetson Nano所需的Linux命令。

- **设备管理：**
  - 设置udev规则以管理Jetson Nano上VESC、激光雷达和摄像头等组件的设备权限。

- **VESC软件：**
  - 安装和配置VESC软件。
  - 确保电机正常运行并设置安全参数。
  - 使用VESC工具进行实时数据分析。

### 第2部分：集成AEV组件并设置仿真环境

项目的第二部分重点是将各种AEV组件集成到ROS系统中，并设置仿真环境。

- **ROS集成：**
  - 将AEV组件集成到ROS系统中。

- **仿真环境：**
  - 使用F1tenth模拟器设置仿真环境进行实验前测试。

- **手动控制和数据分析：**
  - 使用操纵杆手动控制AEV。
  - 调整车辆里程表。
  - 使用集成到AEV系统中的传感器（如激光雷达和摄像头）数据进行实验。

### Bonus实验 CV计算机视觉

- **摄像头集成：**
  - 通过展示EV利用捕获的数据检测和响应人员，成功展示了摄像头的集成。
  - 工作流程图展示了依赖于DNN（深度神经网络）推理库的检测过程。

- **检测算法：**
  - 实现了一个名为“detect_person/confidence”的主题，用于发布基于Linux操作的置信节点，从而仅对EV前方的人做出选择性响应。

- **导航算法：**
  - 创建了一个新的AEV导航算法，利用ROS（机器人操作系统）中的发布和订阅原则。

### 结果

- 在自主车辆环境中实现了系统集成和数据处理的全面理解和实际应用。

