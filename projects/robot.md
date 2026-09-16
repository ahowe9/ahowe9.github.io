# Computer Vision Robotic Drawing Arm

## Overview

As part of a team project, I helped develop a computer vision system that allowed a robotic arm to reproduce images using a Sharpie attached to its end effector.

The system takes an input image, identifies the curves that make up the drawing, and converts the detected geometry into paths that the robotic arm can follow.

## Computer Vision

My primary contribution was helping develop the algorithm used to detect different curves within an input image. The goal was to transform the visual information in the image into a set of continuous paths that could be followed by the robot.

The algorithm processed the image to identify relevant curve features while filtering out information that was not part of the desired drawing. The resulting curve information was then used to generate a path for the robotic arm.

## Robotic Integration

The detected curves had to be translated into motion that the robotic arm could physically execute. The generated paths were passed to the robot so that its end effector could trace the curves while maintaining contact between the Sharpie and the drawing surface.

This required considering both the geometry of the detected curves and the physical limitations of the robotic arm.

## Results

The completed system allowed the robotic arm to interpret an input image and reproduce its curves using a Sharpie. The project demonstrated the integration of computer vision, geometric path generation, and robotic motion.

### Test Images

![](/docs/assets/images/ThisIsFine.png)

*The original image sent to the program*


![](/docs/assets/images/ThisIsFineDraw.jpeg)

*The resulting drawing from the robot arm*

### Skills & Tools

* ROS
* Computer vision
* Image processing
* Curve detection
* Path generation
* Robotics
* Robotic arm programming
* Algorithm development
