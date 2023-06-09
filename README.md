# Dynamics and Force control of a 3 DOF manipulator with PID stiffness controller

<p align="justify">
This project focuses on modelling the dynamics of a 3 DOF robotic manipulator using Euler-Lagrange methods. The dynamical equations of motion are formulated in terms of joint positions, velocities, accelerations, inertia, Coriolis/centrifugal and gravity terms. The robot is modelled using the Peter Corke robotics toolbox in Python. Designed to be a pick and place robot, a PID based stiffness controller is implemented to enable and simulate the robot reaching four corners of a box in Cartesian space with minimal overshoot, while holding a payload.
</p>

## Project implementation in form of GIF file

<p align="justify">
The GIF below shows the implementation of a PID based stiffness controller on the robot while holding a payload, to reach four corners of a box.
  
</p>

<p align="center">
  
  <img src = "https://github.com/sanchit3103/manipulator_dynamics_and_control/assets/4907348/2f5cd54f-a33c-411c-8785-49e9ef742e79" height="400"/>

</p>

## Details to run the code

* <b> main.ipynb: </b> Notebook which includes the formulation of dynamics and implementation of PID controller.
