# Robotic-Manipulator-Simulation

## Overview
This project provides a comprehensive simulation of a 6 Degrees of Freedom (DOF) robotic manipulator using MATLAB and Simulink. The simulation models forward and inverse kinematics, joint space trajectory planning, and dynamic analysis based on the Denavit-Hartenberg (DH) parameter convention.

## Features
- Forward Kinematics: Calculation of the Homogeneous Transformation Matrix (HTM) for each joint and the end-effector.
- Inverse Kinematics: Determination of joint angles to achieve a desired end-effector position.
- Trajectory Planning: Smooth joint-space trajectory generation using higher-order polynomial interpolation.
- Dynamic Simulation: Visualization of the robotic arm's motion in a 3D workspace.
- Path Optimization: Ensures smooth and accurate robotic arm movements.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Robotic-Manipulator-Simulation.git
    ```
2. Open MATLAB and navigate to the project directory.

## Usage
- Modify the DH parameters to simulate different robotic arm configurations.
- Use `Matrixvalues` function to compute the homogeneous transformation matrix from a position vector and Euler angles.
- Run inverse kinematics to find joint angles for a desired end-effector position.
- Plot and visualize the robotic arm's motion and trajectory.

## File Structure
```
/Robotic-Arm-MATLAB-Simulation
│
├── Matrixvalues.m               # Function to compute homogeneous transformation matrix
├── kinematics.m        # Inverse kinematics solver
├── DHparameter.m # DH matrix setup and analysis
└── README.md                 # Project documentation
```

## Dependencies
- MATLAB (R2020a or later recommended)
- Simulink
- Symbolic Math Toolbox

## Contributions
Feel free to open issues, suggest improvements, or fork the repository for your own robotic simulations!

## License
This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
Special thanks to **Manas Kumar Mishra** and **Vishnu** for the foundational work on the robotics model and electronics support.

---
⭐ **If you find this project helpful, please give it a star!** ⭐

