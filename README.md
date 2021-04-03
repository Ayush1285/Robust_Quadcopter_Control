# Robust_Quadcopter_Control

## Introduction
  In this project,we will learn the dynamics of the Quadcopter and the implementation of control algorithms on it.
## Table of contents
  * [Study of Quadcopter Dynamics and 3D rotations.](#Study-of-Quadcopter-Dynamics-and-3D-rotations)
  * Altitude control of a 1D Quadcopter.
  * 2D trajectory tracking using PID controller.
  * 3D trajectory tracking using PID controller.
  * Simulink modelling of Quadcopter.
  * Linear Quadratic Regulator(LQR) on the Quadcopter.
  * Comparison of PID and LQR control system on the Quadcopter.
## Study of Quadcopter Dynamics and 3D rotations
  Following resources were used for dynamics study:
  * [Robotics: Aerial Robotics, by UPenn](https://www.coursera.org/learn/robotics-flight?=)
  * [Euler Quaternions PDF](https://www.ccs.neu.edu/home/rplatt/cs5335_fall2017/slides/euler_quaternions.pdf)
  * [Visualizing Quaternions](https://eater.net/quaternions/)
  * [State Space, by MATLAB Tech Talks](https://www.youtube.com/playlist?list=PLn8PRpmsu08podBgFw66-IavqU2SqPg_w)
  * [Dynamic modeling, Simulation and PID controller of Unmanned Aerial Vehicle UAV](https://drive.google.com/file/d/17vC72CxguJSLH8T1SG_DPBBhd8WRzE7P/view?usp=sharing)
  * [Modelling and Stabilizing Control laws design based on Backstepping for an UAV type Quadrotor](https://drive.google.com/file/d/1x7zfYDEAd4OGHKVt8xIQ0uwxMXA-TSl7/view?usp=sharing)

## Altitude control of a 1D Quadcopter
### Hover at height 0 m

![](https://github.com/Ayush1285/Robust_Quadcopter_Control/blob/main/1-D%20Quadcopter%20Control/Results/Hover%20at%20height%200m.gif)

### Hover at height 1 m

![](https://github.com/Ayush1285/Robust_Quadcopter_Control/blob/main/1-D%20Quadcopter%20Control/Results/Hover%20at%20height%201m.gif)

## 2D trajectory tracking using PID controller
  Our goal was to track the given two dimensional trajectories while minimising the position error.
### Line Trajectory

![](https://github.com/Ayush1285/Robust_Quadcopter_Control/blob/main/2-D%20Quadcopter%20Control/Results/Line%20Traj.gif)

### Sine Trajectory

![](https://github.com/Ayush1285/Robust_Quadcopter_Control/blob/main/2-D%20Quadcopter%20Control/Results/Sine%20Traj.gif)

## 3D trajectory tracking using PID controller
  Our goal was to track the given three dimensional trajectories while minimising the position error.
### Line Trajectory

![](https://github.com/Ayush1285/Robust_Quadcopter_Control/blob/main/3-D%20Quadcopter%20Control/Results/line%20traj.gif)

### Helix Trajectory

![](https://github.com/Ayush1285/Robust_Quadcopter_Control/blob/main/3-D%20Quadcopter%20Control/Results/helix%20traj.gif)

### Minimum Snap Trajectory through given waypoints

![](https://github.com/Ayush1285/Robust_Quadcopter_Control/blob/main/3-D%20Quadcopter%20Control/Results/min%20snap%20traj.gif)

## Simulink modelling of the Quadcopter
  * Dynamics Study of the Quadcopter according to the paper [Modelling and Stabilizing Control laws design based on Backstepping for an UAV type Quadrotor](https://drive.google.com/file/d/1x7zfYDEAd4OGHKVt8xIQ0uwxMXA-TSl7/view?usp=sharing)
  * Linearized the equations around hovering point.
  * Developed the linear simulink model of Quadcopter.
