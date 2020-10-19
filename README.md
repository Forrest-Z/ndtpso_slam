NDTPSO-SLAM
===========

NDTPSO-SLAM is a ROS package which provides an inhanced implementation of the scan matching algorithm proposed in [2] which optimizes the implementation of [1].
It uses NDT (Normal Distribution Transform) to model the environnement and PSO (Particle Swarm Optimisation) to perform the scan matching and solve the pose problem.

This package has been tested with ROS Melodic on Ubuntu 18.04.

This project is devided to two parts, the `libndtpso_slam` which is a C++ library that implements the proposed scan matching method, and in the other part, the ROS node `ndtpso_slam_node` which provides the ROS interface to this library.

### Maintainer:
Abdelhak BOUGOUFFA, Paris-Saclay University, SATIE Laboratory
<`abdelhak [dot] bougouffa [at] universite-paris-saclay.fr`>

### To cite this work:
- [1]: **Sara BOURAINE**, **Abdelhak BOUGOUFFA** and **Ouahiba AZOUAOUI**, _NDT-PSO, a New NDT based SLAM Approach using Particle Swarm Optimization_, 16th International Conference on Control, Automation, Robotics and Vision (ICARCV), 2020 (Submitted).
- [2]: **Abdelhak BOUGOUFFA**, **Emmanuel SEIGNEZ**, **Samir BOUAZIZ** and **Florian GARDES**, _SmartTrolley: An Experimental Mobile Platform for Indoor Localization in Warehouses_, 16th International Conference on Control, Automation, Robotics and Vision (ICARCV), 2020 (Submitted).
