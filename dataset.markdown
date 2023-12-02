---
layout: page
title: ROAM Dataset
description: Robot Automation and Motion Dataset
permalink: /dataset/
---

# About
We introduce the **Robot Autonomous Motion (RoAM)** video dataset, which is collected with a custom-made turtlebot3 Burger robot in a variety of indoor environments recording various human motions from the robot's ego-vision. The dataset also includes synchronized records of the LiDAR scan and all control actions taken by the robot as it navigates around static and moving human agents. The unique dataset provides an opportunity to develop and benchmark new visual prediction frameworks that can predict future image frames based on the action taken by the recording agent in partially observable scenarios or cases where the imaging sensor is mounted on a moving platform.

![](/images/fig_roman_burger_mod.png){: .center-image }
*Turtlebot3*

# RoAM Data

The RoAM dataset is collected using a custom-built Turtlebot3 Burger robot. We have used Zed mini stereo vision camera for capturing the left and right timestamped image pairs. Other than that the robot is equipped with an LDS-01 2-dimensional LiDAR, a TP-link WiFi communication module as shown in Figure above. The Turtlebot3 employs two DYNAMIXEL XL430-W250 servo motors for navigation, utilizing current-based torque control. These motors are actuated and controlled by the OpenCR-01 board, which is integrated into the platform. For our specific application, we have selected the Jetson TX2 board as the onboard computer, operating on the ROS Melodic framework and the Ubuntu 18.04 operating system. This setup offers the advantage of leveraging the Jetson TX2's high computational power to support complex robotic tasks, such as perception, navigation, and machine learning.
![](/images/fig_roman_processed_data.png){: .center-image }
*The processed data file structure of RoAM*

# TurtleBot3 Data Download

The initial version of the dataset is currently available in TFRecord file format. To download the dataset, please drop an email to <meenakshisar@iisc.ac.in> with the subject line **Access to RoAM dataset** along with your affiliation and purpose to use for the dataset. 



# Download Links

[LegoBot Dataset](http://bit.ly/IIScRoM)

[TurtleBot3 Dataset](https://drive.google.com/folderview?id=15x2n33EHm46spig6oP6ToOuRtUTcGC--)
