## Mathematical modeling of aircraft runway alignment

## Introduction
This project explores the mathematical logic behind the aircraft autonomous landing where the image of a 2D camera transforms into a 3D spacial data of the runway, helping pilots visualize the landing in a more precise way.   

## Objectives:
- Define the transition between 2D pixel coordinates to 3D world coordinates. 
- Analyze how rotation matrices and translation vectors describe the aircraft's position relative to the runway. 
- Understand the role of probability in reducing "noise" caused by aircraft vibrations and atmospheric conditions.

## Core of the problem
The main aviation challenge in vision-based landing(the one that uses a camera in order to faciliate the job of the pilot or is completely anonomous) is extracting 3D information from 2D image data in order to determine the position of the plane relative to the runway. 

## The intrinsic camera matrix. 
Intrinsic parameters of a camera are related to the camera itself, regardless of where it is placed. In order to explain how a camera perceives the three-dimensional world, we use the camera intrinsic matrix K - a 3x3 matrix that encodes the internal parameters of a camera: the focal lengtх, known better as the "zoom"(f_x, f_y) and the principal point(c_x, c_y), which is typically the center of the image. K defines the relationship between 3D coordinates and their 2D projectиons in the camera image. In the context of autonomous landing, K tells us exactly how a point on the runway appears as a pixel in the camera image. 


