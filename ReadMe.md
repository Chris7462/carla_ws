# Carla Workspace

## TL; DR
### Clone repository:
```bash
git clone --recurse-submodules https://github.com/Chris7462/carla_ws.git
cd carla_ws
colcon build --symlink-install
source ./install/setup.bash
```

### Launch Carla
```bash
ros2 launch carla_launches carla_launch.py
```

## Introduction
In the realm of autonomous driving, accurate localization and robust perception are crucial components for ensuring the safety and efficiency of vehicles. This project aims to leverage the [Carla simulator](https://carla.org/) to showcase advancements in localization and perception algorithms, contributing to the ongoing development of autonomous systems.

## Perception
The perception module includes the development of the perception system using deep learning techniques for segmentation, object detection, object tracking, and lane detection.
<!--
* Utilize convolutional neural networks (CNNs) or other relevant models to identify and track objects such as vehicles, pedestrians, and cyclists.
* Assess the performance of the perception system by measuring metrics like precision, recall, and F1 score, and evaluate its generalization across diverse scenes.
-->

## Localization
The localization module encompasses implementations of state-of-the-art localization algorithms, such as Simultaneous Localization and Mapping (SLAM), Visual Odometry, and LiDAR Odometry. More details can be found in localization module.

<!--
* Implement state-of-the-art localization algorithms, such as Simultaneous Localization and Mapping (SLAM), Visual Odometry, of LiDAR Odometry, using the KITTI dataset.
* Evaluate the performance of the localization system in different scenarios, including urban environments, highways, and challenging weather conditions.
* Visualize and analyze the accuracy and robustness of the localization algorithm through metrics like trajectory error, pose estimation, and consistency.
-->
