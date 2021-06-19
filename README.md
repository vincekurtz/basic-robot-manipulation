# Robot Manipulation Basics

This repository contains a series of Google Colab notebooks for learning about the basics of robot manipulation with a simulated Kinova Gen3 robot arm.

## Getting Started

We'll use [Google Colab]() to run a simulation of our robot, a [Kinova Gen3]() robot arm. Google Colab allows us to run the simulation "in the cloud" on Google's servers, so you don't need to worry about installing software and dependencies on your own computer.

The notebooks in this repository can be opened directly in Colab [here](https://colab.research.google.com/github/vincekurtz/basic-robot-manipulation/blob/main/), or using the links below. They will make most sense if you go in order, starting from `01_colab-intro.ipynb`. 


### [Colab Intro](https://colab.research.google.com/github/vincekurtz/basic-robot-manipulation/blob/main/01_colab-intro.ipynb)

This notebook takes you through the basics of the Colab interface. 

### [Simulation Basics](https://colab.research.google.com/github/vincekurtz/basic-robot-manipulation/blob/main/02_simulation-basics.ipynb)

Outlines the basic usage of the simulation, including controlling the robot manually.

### [Control System](https://colab.research.google.com/github/vincekurtz/basic-robot-manipulation/blob/main/03_control-system.ipynb)

Provides an overview of the KinovaStation system, and introduces the idea of creating a control system that goes along with it. 

### [Camera](https://colab.research.google.com/github/vincekurtz/basic-robot-manipulation/blob/main/04_camera.ipynb)

Shows how to use the (simulated) RGB camera on the robot in a control loop. 

### Future Notebooks

Some possible topics for future notebooks:

- Adding different objects to the scene
- Using the depth camera
- Geometric grasp planning
- Torque control
- Hardware interface (?)

