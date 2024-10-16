# Quadrotor Control Using Modern Control Techniques

This project demonstrates the control of a quadrotor using advanced control techniques, including both linear and nonlinear modeling approaches. The project involves designing a state-feedback controller and simulating the performance in MATLAB Simulink to evaluate the stability and trajectory tracking of the quadrotor.


## Project Overview

The goal of the project is to control the orientation and position of the quadrotor by adjusting the motor speeds based on the system's state. We used modern control methods, including state-space representation, pole placement, and pre-compensation techniques to achieve optimal control of the system.

## Key Features

- **Nonlinear System Modeling**: The quadrotor's dynamics are derived in a nonlinear form, accounting for the rotational and translational motion.
- **Linearized Model**: The system is linearized around a hover point to simplify controller design.
- **State Feedback Control**: A state-feedback controller is designed using pole placement to stabilize the quadrotor and follow desired trajectories.
- **Simulink Simulations**: The system is implemented in MATLAB Simulink, where we simulate the quadrotor's response to different control inputs and disturbances.

## Modeling and Control

- **System States**: The quadrotor's state includes its position (X, Y, Z) and orientation (ϕ, θ, ψ) as well as their corresponding velocities.
- **Nonlinear and Linear Models**: The nonlinear equations of motion are derived, and the system is linearized for controller design around equilibrium.
- **Controller Design**: A state-feedback controller is designed using the pole placement method to ensure the stability of the quadrotor and track reference signals. A pre-compensator is also used for reference tracking.
- **Simulations**: We performed simulations to verify the controller performance, including response to step and sinusoidal reference inputs and rejection of disturbances.

## Visualizations and Results


- **Trajectory Simulation**: The simulation results show the quadrotor's response in tracking various trajectories, including position and orientation.
- **Comparison**: Both linear and nonlinear models are compared in terms of response time and accuracy.

## Setup Instructions

1. Clone the repository to your local machine.
2. Open the MATLAB Simulink model provided.
3. Run the simulations to observe the system's response to different inputs and disturbances.

## Future Enhancements

- Implementing more advanced nonlinear control techniques such as sliding mode control.
- Expanding the model to include other environmental factors like wind disturbances.

## Visuals

![Trajectory Simulation](path-to-your-image)

[Watch the Simulation Video]([link-to-your-video](https://github.com/dorsa-rh/Quadrotor-modern-control/blob/main/result.MP4))
