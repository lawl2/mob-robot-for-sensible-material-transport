# Autonomous Mobile Robot for sensible material transport

## The aim of the project

In a biological laboratory there’s the need to keep cell’s vials safe and to conserve them in a box containing liquid nitrogen
This box stands in a refrigerated room and it’s possible to move it around to bring the vials to scientists to perform experiments

This project has the aim to simulate a mobile robot which is able to transport these vials autonomously, avoiding possible obastcles, to a scientist workstation in a goal position

![locator-thermo-scientific-locator-cryobiological-inventory-systems-2663](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/ce146a66-826e-4522-8fa8-a93fe866ce14)


## Schematic view of the project

### Modeling of the world

* Creation of the laboratory in GAZEBO

  ![laboratory-gazebo2](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/f7c4c390-22d4-4535-8d9e-bad3658fb917)


### Modeling the robot

* Definition of a Differential Drive Robot
* Combining URDF and .xacro to create the model

  ![Modeling_URDF-collision](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/40e6db82-16bd-4663-9cc9-88818a389572)


### Simulation

* ROS2 + GAZEBO + Rviz
* Spawning robot with all the sensors in Gazebo and Rviz

  ![camera-gazebo](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/8d2ffae6-682e-4f4b-942e-d28a38a357bb)
  ![camera-rviz](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/d1f646af-c4c5-468b-8335-0961f894a050)
![depth-gazebo](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/0482ab00-3b84-498e-b3cc-1e93171a605c)
![depth-rviz](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/2d666a5f-b675-4c59-99e6-e45cd7227f8f)
![lidar_rviz](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/22cc8dbd-915f-43bf-864d-ad48cdc859d2)
![lidar-gazebo](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/39d598b6-77e4-4b72-87c2-98850b8b2212)


### Controlling

* Gazebo control
* ros2_control
* Teleoperation
* Final definition of the launch file

### Mapping & Localization

* ROS & SLAM
* Localization using SLAM
* Localization using AMCL

  ![mapping-rviz](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/462628ca-3d66-48a9-a8e1-867ddafca797)
  ![mapping-rviz2](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/c4d41075-67a7-4f82-b3d8-3a76b463ab3a)
![mapping-rviz3](https://github.com/lawl2/mob-robot-for-sensible-material-transport/assets/105045290/35382563-1450-4703-9236-b3d239494ae0)


