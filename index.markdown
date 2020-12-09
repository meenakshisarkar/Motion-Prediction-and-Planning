---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Ability to predict is a fundamental component of intelligence. Video prediction often decodes much useful information about the surroundings in a format which is rich in information and can be exploited by learning algorithms. While long term video prediction remains a challenging learning problem, the problem of motion prediction in robotics is even more complex. This added complexity is due to the fact that in robotics the camera is usually mounted on a moving base. Movement of the robot affects the predicted video frames. Thus, the prediction framework will not only have to predict the motion of the dynamic objects in the camera frame but also understand how the motion of the robot affects and interacts with the generated future frames.

Unfortunately, the datasets that are currently generally available are not designed to address the problem of motion prediction for a moving camera. The RoboNet dataset comprises various platforms and lighting conditions but only for a manipulator pushing various objects where the camera is fixed. But, we aim to help researchers work with scenarios where the bot is in motion and is required to efficiently plan its motion and avoid obstacles.

In order to establish the baseline for our work on robot motion prediction problem with moving camera base, we recorded the motion of robotic agents navigating under different scenarios. The dataset currently consists of data recorded using two different robotic platforms: Turtlebots and LEGO robots. In order to improve generalization, we have recorded the dataset under different indoor and outdoor scenarios with varying lighting using two different camera models.

This is a work in progress. We plan on capturing videos using other robotic platforms like Turtlebot 2i and aerial drones etc and also using multiple moving bots from the viewpoint of bots like Turtlebot3. This part of the dataset will also be captured in various indoor and outdoor scenarios under various lighting conditions in order to closely mimic the real-world conditions.
