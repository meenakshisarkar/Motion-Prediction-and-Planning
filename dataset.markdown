---
layout: page
title: ROAM Dataset
description: Robot Automation and Motion Dataset
permalink: /dataset/
---

# About
The dataset currently consists of data recorded using two different robotic platforms: **Turtlebots** and **LEGO robots**.

![](/images/robots3.PNG){: .center-image }
*Turtlebot3 (Left), Lego Mindstorms (right)*

# LegoBot Data

The Lego Mindstorms bot moving at an average speed of 18 cm/s was connected via Blue-tooth to execute 4 different types of trajectories- Straight path, Inclined path (left to right and right to left) and Arc, with 3 different depths from the stationary mounted-camera in each of the scenarios. About 1.5 hours of data was recorded with the help of a GoPro Hero5 camera at 30 fps, with a resolution of 720×1280.

* **Atrium:** The smooth floor attributes to consistent motion trajectories without any jerks in an indoor environment. There are two subcategories *Atrium Daylight & Atrium Night* (with Halogen Light).

* **Pavement (Outdoor Env.):** The ground (lock-tiles) intrinsically adds periodic inconsistency in motion and is bright-colored. A sun-lit scene with nearby tree canopy (shadows in the backdrop).

* **Airstrip (Outdoor Env.):** The Lego bot's motion was the most jittery here due to the asphalt.

![](/images/Lego_frames.png){: .center-image }
*Atrium (daylight and night), Airstrip, Pavement [clockwise]*

# TurtleBot3 Data

The TurtleBot3 was automated to move on a straight trajectory at a velocity of 10 cm/s with periodic turns and random human motion. Videos were recorded by the turtlebot with the help of a Raspberry Pi V2 camera with a Sony IMX219 8-megapixel sensor at 30fps. About 1.4 hours of data was recorded in different scenarios with variation in both environment and lighting.

* **Corridor (Indoor Env.):** The smooth floor of the corridor attributes to consistent motion trajectories without any jerks. The floor also provides some amount of reflection that helps facilitate variety in the data. There are two subcategories *Corridor Noon & Corridor Evening*.

* **Pavement (Outdoor Env.):** This setting is well-lit with natural sunlight and also has shadows of nearby trees. The ground (lock-tiles) adds intrinsic inconsistency in motion and is bright-colored.

* **Lab Floor (Indoor Env.)** This setting is completely indoor and only has artificial lighting. There are a variety of other objects like chairs, tables and bag that introduce more variety in the environment.

![](/images/turtlebot_frames.png){: .center-image }
*Pavement, Corridor (noon) , Lab, Corridor (evening) [clockwise]*

# Download Links

[LegoBot Dataset](http://bit.ly/IIScRoM)

[TurtleBot3 Dataset](https://drive.google.com/folderview?id=15x2n33EHm46spig6oP6ToOuRtUTcGC--)
