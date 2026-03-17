## Mathematical modeling of aircraft runway alignment

## Introduction
This project explores the mathematical logic behind the aircraft autonomous landing where the image of a 2D camera transforms into a 3D spacial data of the runway, helping pilots visualize the landing in a more precise way.   

## Objectives:
- Define the transition between 2D pixel coordinates to 3D world coordinates. 
- Analyze how rotation matrices and translation vectors describe the aircraft's position relative to the runway. 
- Understand the role of probability in reducing "noise" caused by aircraft vibrations and atmospheric conditions.

## Core of the problem
The main aviation challenge in vision-based landing(the one that uses a camera in order to faciliate the job of the pilot or is completely anonomous) is extracting 3D information from 2D image data in order to determine the position of the plane relative to the runway. 

## How to run
Install the required libraries:
pip install numpy matplotlib opencv-python

## Structure
- Aviation_math.ipynb — main notebook with all analysis and code




