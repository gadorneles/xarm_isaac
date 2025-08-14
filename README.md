# XArm Isaac Sim Integration

![alt text](assets/image.png)

<div align="center">

[![Isaac Sim](https://img.shields.io/badge/Isaac_Sim-5.0.0-green.svg?style=for-the-badsge&logo=nvidia)](https://developer.nvidia.com/isaac-sim)
![ROS2](https://img.shields.io/badge/ROS2-Humble-blue?style=for-the-badsge&logo=ros)
![Python](https://img.shields.io/badge/python-3.10-blue?style=for-the-badsge&logo=python)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-grey.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Last Commit](https://img.shields.io/github/last-commit/gadorneles/xarm_isaac.svg?style=for-the-badsge)](https://github.com/gadorneles/xarm_isaac/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/gadorneles/xarm_isaac)](https://github.com/gadorneles/xarm_isaac/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/gadorneles/xarm_isaac)](https://github.com/gadorneles/xarm_isaac/pulls)
[![Contributors](https://img.shields.io/github/contributors/gadorneles/xarm_isaac.svg)](https://github.com/gadorneles/xarm_isaac/graphs/contributors)
[![Github Stars](https://img.shields.io/github/stars/gadorneles/xarm_isaac.svg)](https://github.com/gadorneles/xarm_isaac/stargazers)

</div>

## Overview

This repository provides integration of the UFactory XArm robotic manipulator series with NVIDIA Isaac Sim, along with simple tasks and ROS2 nodes for controlling the robot. It has full compatibility with the MoveIt2 nodes from the [xarm_ros2](https://github.com/xArm-Developer/xarm_ros2) package.

## Installation

### Prerequisites

- [NVIDIA Isaac Sim 5.0.0](https://developer.nvidia.com/isaac-sim)
- [ROS2 Humble](https://docs.ros.org/en/humble/Installation.html)

### Setup

1. **Clone the repository:**
   ```bash
   cd ~/xarm_ws/src
   git clone <repository-url> xarm_isaac
   ```

2. **Build the package:**
   ```bash
   cd ~/xarm_ws
   colcon build --packages-select xarm_isaac
   source install/setup.bash
   ```

## Changelog

### [Unreleased]
- Initial repository setup
- Basic XArm6 USD assets

## Future Goals

- [ ] Support for additional XArm models (XArm5, XArm7)
- [ ] Add full support for RealSense d435i
- [ ] Make ROS2 examples and launchfiles available
- [ ] Implement basic manipulation tasks (pick and place)
- [ ] Isaac Lab integration

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- UFactory for the XArm robot series
- NVIDIA for Isaac Sim platform
- ROS2 community for the robotics framework