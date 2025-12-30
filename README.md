Robotics-
Kinematic Analysis of STANFORD Robot using RoboAnalyzer


# Demystifying Kinematic Analysis of STANFORD Robot using RoboAnalyzer

This repository is based on my article **[Demystifying Robotics: A Deep Dive into the STANFORD Robot and RoboAnalyzer](https://medium.com/@manojreddy2404/demystifying-robotics-a-deep-dive-into-the-stanford-robot-and-roboanalyzer-ab7310a482d9)**.  
It explores the **STANFORD robot**, one of the earliest and most studied 6-DOF serial manipulators, using the simulation tool **RoboAnalyzer**.

---

## 📌 Project Overview

--> This project presents a simulation-based kinematic analysis of the STANFORD robot, a classical 6-degree-of-freedom (6-DOF) serial manipulator, using RoboAnalyzer.

--> The analysis focuses on forward kinematics, inverse kinematics, frame transformations, workspace visualization, and joint-level motion characteristics such as angle, velocity, and acceleration.

--> This project was originally completed in 2022 as part of academic coursework and is now documented for open-source reference and portfolio presentation.

---

## About the STANFORD Robot

--> Type: 6-DOF serial manipulator

--> Joint Configuration: 5 revolute + 1 prismatic joint

--> Reach: ~1 meter

--> Payload Capacity: ~5 kg

--> Control: Computer-controlled

The STANFORD robot is historically significant and widely used in robotics education and research, serving as a foundation for modern manipulator design.


## Software Used

--> RoboAnalyzer

--> 3D model-based robotics simulation tool

--> Developed by IIT Delhi

--> Supports kinematic, dynamic, and workspace analysis

Official Website: http://www.roboanalyzer.com/

## Kinematic Analysis Performed

1. Denavit–Hartenberg (DH) Modeling
   Standard DH parameters were used to define:
     * Joint offset
     * Joint angle
     * Link length
     * Twist angle
     * Frame transformations were visualized for each joint

2. Forward Kinematics
   End-effector position and orientation computed from joint parameters
   
     * Initial and final end-effector configurations analyzed
     * End-effector trajectory visualized during motion

 4. Inverse Kinematics
    Numerical methods used to compute joint values for a desired end-effector pose
     * Enabled validation of reachable configurations

5. Joint and Link Motion Analysis
   The following plots were generated using RoboAnalyzer:
     * Joint angle vs time
     * Joint velocity vs time
     * Joint acceleration vs time
     * Link position along X, Y, Z axes

6. Workspace Analysis
   Visualized reachable workspace of the robot
     * Identified motion limits and safe operating regions

📊 Results and Key Learnings
     * Visual understanding of kinematic chains and frame transformations
     * Efficient evaluation of joint-level motion characteristics
     * Demonstrated advantages of simulation over manual analytical method
     * Strengthened understanding of serial manipulator behavior
     * All plots and outputs are available in the results/ directory.

## 📂 Repository Structure
├── images/     → Simulation screenshots & figures

├── results/    → Graphs and plots

├── models/     → RoboAnalyzer robot model

├── docs/       → Project report (PDF)


## Acknowledgements

  * RoboAnalyzer Team, IIT Delhi
  * Stanford AI Laboratory (historical robot model)

