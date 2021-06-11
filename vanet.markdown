---
layout: page
title: VANet
description: Velocity Acceleration Network
permalink: /vanet/
---

# About
 We propose a novel deep learning framework that focuses on decomposing the motion or the flow of the pixels from the background for an improved and longer prediction of video sequences. We propose to generate multi-timestep pixel level prediction using a framework that is trained to learn the temporal and spatial dependencies encoded in  video data separately. The proposed framework called Velocity Acceleration Network or VANet is  capable of predicting long term video frames for the static scenario, where the camera is stationary, as well as the dynamic partially observable cases, where the camera is mounted on a moving platform (cars or robots). This framework decomposes the flow of the image sequences into velocity and acceleration maps and learns the temporal transformations using a convolutional LSTM network. Our detailed empirical study on three different  datasets (BAIR, KTH and KITTI) shows that conditioning recurrent networks like LSTMs with higher order optical flow maps results in improved inference capabilities for videos. 
# Architecture of VANet 
![](/images/VANet.png){: .center-image }
<!-- *Turtlebot3 (Left), Lego Mindstorms (right)* -->
# BAIR Towel Pick Dataset 
<!-- (https://sites.google.com/berkeley.edu/robotic-interaction-datasets/home) -->
<!-- Ground Truth               |  VANet                     | MCNet                    |  SVG
:-------------------------:|:--------------------------:|:------------------------:|:-------------------------: -->
![](/images/gt.gif){:height="150px" width="150px"}    ![](/images/VANet.gif){:height="150px" width="150px"} ![](/images/MCNet.gif){:height="150px" width="150px"}    ![](/images/svg.gif){:height="150px" width="150px"}
*Results from Ground Truth, VANet, MCNet and SVG respectively (from left to right)*
<!-- <p float="center"> -->
<!-- <img src="/images/gt.gif" width="425"/>  <img src="images/VANet.gif" width="425"/>  <img src="images/MCNet.gif" width="425"/> <img src="images/svg.gif" width="425"/>   -->
<!-- </p> -->
# KITTI Dataset
<!-- (https://sites.google.com/berkeley.edu/robotic-interaction-datasets/home) -->
<!-- Ground Truth               |  VANet                     | MCNet                    |  SVG
:-------------------------:|:--------------------------:|:------------------------:|:-------------------------: -->
![](/images/kitti_gt.gif){:height="150px" width="150px"}    ![](/images/kitti_vanet.gif){:height="150px" width="150px"} ![](/images/kitti_mcnet.gif){:height="150px" width="150px"}    ![](/images/kitti_svg.gif){:height="150px" width="150px"}
*Results from Ground Truth, VANet, MCNet and SVG respectively (from left to right)*

[Link to Code](https://github.com/meenakshisarkar/vanet-pmlr.git)

[Link to Paper](https://preregister.science/papers_20neurips/85_paper.pdf)

## Citation
If you are using VANet, please cite our proposal paper as:
```
@inproceedings{vanet,
  title={Decomposing camera and object motion for an improved video sequence prediction},
  author={Meenakshi Sarkar and Debasish Ghose},
  booktitle={Pre-registration workshop NeurIPS (2020), Vancouver, Canada},
  pages={},
  year={2020}
}
```
##

## Link to the final results paper in PMLR will be updated soon.

