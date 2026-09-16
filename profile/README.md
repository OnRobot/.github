<p align="center">
  <img src="assets/onrobot-logo.png" alt="OnRobot" width="280">
</p>

<h1 align="center">Develop with OnRobot tools</h1>

<!-- <p align="center"><strong>One system, zero complexity.</strong></p> -->

OnRobot provides the physical interaction layer connecting simulation, real-world interaction data and physical device control across Physical AI workflows.
Access simulation assets, ROS 2 packages, the C++ Tool API and technical resources for supported OnRobot grippers, sensors, and end-of-arm tools.

## From simulation to physical control

Move through three connected stages: build, train and validate with digital gripper models, bring real-world gripper data into Physical AI workflows, and control supported physical tools.

| Stage | What you can do |
| --- | --- |
| **Simulate** | Simulate your application, generate simulated data, and train your AI model in NVIDIA Isaac Sim using OnRobot gripper models that represent the geometry, movement, and relevant physical behavior of the real device. |
| **Collect** | Integrate force, contact, position, and device-state data into data-collection and Physical AI training workflows through standardized interfaces. |
| **Control** | Control supported physical OnRobot grippers through standardized interfaces, using command-based or real-time control while receiving continuous feedback. |

## Explore the developer stack

| Repository | What it provides |
| --- | --- |
| [OnRobot Tool API](https://github.com/OnRobot/onrobot-tool-api) | A standalone C++17 library for integrating supported OnRobot grippers over Modbus TCP or Modbus RTU. A strong foundation for embedded, industrial, and host-side applications. |
| [OnRobot ROS 2](https://github.com/OnRobot/onrobot-ros2) | ROS 2 packages that bring OnRobot grippers into familiar robotics workflows for integration, control, data collection, and experimentation. |
| [OnRobot grippers for Isaac Sim](https://github.com/OnRobot/onrobot-isaacsim) | Simulation-ready gripper models for NVIDIA Isaac Sim. Explore virtual workcells, validate configurations, and shorten the path from simulated to physical testing. |

## Start building

Choose the path that matches your work: begin with Isaac Sim for digital
validation, ROS 2 for robotics workflows, or the Tool API for direct gripper
integration. Each repository contains its supported products, environments,
versions, release notes, licensing, documentation, and issue-reporting
guidance.



For help choosing an integration path or preparing for real-hardware
validation, [talk to an OnRobot expert](https://onrobot.com/en/talk-to-an-expert).
