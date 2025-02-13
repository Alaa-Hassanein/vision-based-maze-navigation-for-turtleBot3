# Autonomous Robot Maze Navigation System

## Overview

This project focuses on developing an **Autonomous Robot Maze Navigation System** that utilizes **computer vision, path planning, and trajectory control** to navigate a TurtleBot3 Waffle robot through a maze. By leveraging **OpenCV, Python, and ROS (Robot Operating System)**, the robot processes images of the maze, determines an optimal path, and follows it efficiently using a **wall tracking algorithm**.

This project is part of a **Mechatronics Project** for the (BSc) **Robotics and Automation Engineering Major** program at **German International University**.

## Special Thanks

We extend our sincere gratitude to **TA Mohamed Madbouly** for his guidance and support throughout this research. We also would like to Thank **German International University (Berlin Campus)** and Its staff for their undying support during the whole project and supplying us with the resources required.

## Dataset and Sources

The robot navigates using a **pre-processed maze image** captured via an IP Webcam. The following methodologies and tools were used to develop the system:

- **Camera Calibration using OpenCV**: A 9x6 chessboard calibration pattern was used to ensure precise image processing.
- **Image Processing for Map Creation**: Contour detection and morphological operations were applied to create a binary map for path planning.
- **Path Planning Algorithm**: The robot follows a **wall tracking algorithm** to move towards the exit while avoiding obstacles.
- **Trajectory Planning**: The velocity and turning angles are dynamically adjusted based on the robot’s distance from the next waypoint.

## Code Inspiration and References

The implementation was inspired by several research papers and open-source repositories, including:

- **Aerial View-Based Guidance System** (Wasti et al.)
- **Graph Theory-Based Maze Solving** (Aqel et al.)
- **TurtleBot3 ROS Implementations**

All references are properly cited in the thesis document.

## Results

After rigorous testing, the system successfully navigated the maze using only **preprocessed map data, without real-time sensor feedback**. The key outcomes include:

- **High Accuracy in Navigation**: The robot followed the designated path with minimal deviation.
- **Efficient Computational Performance**: ROS and OpenCV enabled fast image processing and decision-making.
- **Scalability**: The approach can be extended for real-world indoor navigation applications.

## Additional Resources

- **Documents**: Available in the **Final Report folder**.
- **Citations**: All references are cited in the Final Report.

## License

This project is developed for academic research purposes. Please refer to the license file for terms of use.

For any questions or collaboration, feel free to contact the authors!

