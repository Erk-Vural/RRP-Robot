# RRP Robot

The RRP Robot is a basic robotic system implemented using MATLAB and the Robotics Toolbox. It consists of two revolute joints followed by a prismatic joint in a serial configuration.

## Features

- **RRP Configuration**: Revolute-Revolute-Prismatic configuration.
- **Forward Kinematics**: Calculate the end-effector position given joint angles.
- **Inverse Kinematics**: Compute joint angles given desired end-effector position.
- **Visualization**: Visualize the robot and its movement in MATLAB.

## Technologies Used

- MATLAB
- Robotics Toolbox

## Installation

1. Install MATLAB on your system if not already installed.

2. Clone the repository:
   ```bash
   git clone https://github.com/your_username/rrp-robot.git
   ```

3. Set up the Robotics Toolbox:
   - Download and install the Robotics Toolbox for MATLAB from [Peter Corke's website](https://petercorke.com/toolboxes/robotics-toolbox/).

4. Open MATLAB and navigate to the project directory.

5. Run the MATLAB scripts to interact with the RRP robot.

## Usage

1. Define the DH parameters of the RRP robot in MATLAB.
2. Use the provided scripts to perform forward and inverse kinematics calculations.
3. Visualize the robot and its movements using MATLAB plotting functions.
4. Experiment with different joint angles and end-effector positions to observe the robot's behavior.
