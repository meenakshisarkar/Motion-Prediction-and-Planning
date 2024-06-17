---
layout: page
title: ROAM Dataset
description: Robot Autonomous Motion Dataset
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

# Samples
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .image-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 20px 0;
        }
        .image-container img {
            height: 160px;
            width: 160px;
            margin: 0 10px;
        }
        .caption {
            text-align: center;
            font-weight: bold;
            margin-top: 10px;
            font-size: 18px; /* Set the text size here */
        }
        .image-container img {
    height: 160px;
    width: 160px;
    margin: 0 10px;
    border: 4px solid green; /* Add a green border around each image */
    box-sizing: border-box; /* Include border in image size */
}
    </style>
</head>
<body>
    <div class="image-container">
        <img src="/images/gt_1.gif" alt="Training Sample 1">
        <img src="/images/gt_2.gif" alt="Training Sample 2">
        <img src="/images/gt_3.gif" alt="Training Sample 3">
        <img src="/images/gt_4.gif" alt="Training Sample 4">
    </div>
    <div class="caption">Training Video Samples</div>
</body>
</html>

# RoAM Dataset Download

The initial version of the dataset is currently available in TFRecord file format. To download the dataset, please drop an email to <meenakshisar@iisc.ac.in> with the subject line **Access to RoAM dataset** along with your affiliation and purpose to use for the dataset. 



## Cite RoAM as:
```
@InProceedings{acpnet2023,
  author={Sarkar, Meenakshi and Honkote, Vinayak and Das, Dibyendu and Ghose, Debasish},
  booktitle={2023 32nd IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)}, 
  title={Action-conditioned Deep Visual Prediction with RoAM, a new Indoor Human Motion Dataset for Autonomous Robots}, 
  year={2023},
  volume={},
  number={},
  pages={1115-1120},
  doi={10.1109/RO-MAN57019.2023.10309423}
}
```
