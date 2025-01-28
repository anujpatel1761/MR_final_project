# Autonomous Robot for Disaster Mapping and Victim Localization

## Project Overview
This project focuses on developing an autonomous robot system capable of mapping disaster environments and identifying victims using AprilTags as stand-ins. The system utilizes Turtlebot3 Burger integrated with ROS Noetic and is designed for deployment in closed, initially unknown environments.

## Team Members
- Michael Potter - Cognitive Systems Lab, Northeastern University
- Anuj Patel - Masters in Robotics, Northeastern University
- Rahil Bhowal - Masters in Robotics, Northeastern University
- Jingming Cheng - Masters in Robotics, Northeastern University
- Richard Zhao - Masters in Computer Science, Northeastern University

## Key Features
- **Autonomous Navigation**: Utilizes SLAM (Simultaneous Localization and Mapping) for navigation and mapping of the environment.
- **Victim Localization**: Employs AprilTags for simulating victim identification and localization.
- **Advanced Algorithms**: Implements a Cubature Kalman Filter to enhance localization accuracy and an exploration algorithm to optimize environment exploration.

## Hardware Setup
- **Robot Model**: Turtlebot3 Burger (TB3)
- **Sensors**:
  - Dynamixel X-series motors for motion control.
  - 360-degree LiDAR sensor (LDS-02) for mapping and obstacle detection.
  - Raspberry Pi Camera for visual data capture and AprilTag detection.

## Software Setup
- **ROS Packages**:
  - `TurtleBot3_description`, `TurtleBot3_bringup` for basic robot setup.
  - `raspicam_node`, `apriltag_ros` for camera operation and AprilTag detection.
  - `TurtleBot3_slam`, `TurtleBot3_navigation`, and `m-explore` for navigation and mapping.
- **Launch Files**:
  - `TurtleBot3_robot.launch` to start the robot's sensor and motion systems.
  - `camerav2_640x624_15fps.launch` to initiate the camera.
  - `continuous_detection.launch` for ongoing AprilTag detection.

## Simulation
- **Gazebo Environments**: Includes multiple Gazebo setups to simulate different search and rescue scenarios, validating the effectiveness of the robot in real-time disaster simulations.

## Repository Links
- Full pipeline code: [GitHub - Full Pipeline Code](https://github.com/rzhao5659/MRProject/tree/main)
- Exploration code: [GitHub - Exploration Code](https://github.com/rzhao5659/MRProject/tree/rz/exploration)

## Acknowledgments
- Professor Everett for his guidance and dedication to robotics education.
- The team members for their collaborative efforts in bringing this project to fruition.

For more detailed information on the setup and operation, please refer to the specific GitHub repository links provided above.
