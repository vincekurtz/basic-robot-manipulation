# Robot Manipulation Basics
This repository contains a series of Google Colab notebooks for learning about the basics of robot manipulation with a simulated Kinova Gen3 robot arm.

## Getting Started

Check out this [introduction to Colab](https://colab.research.google.com/notebooks/basic_features_overview.ipynb)

- [Start Here](https://colab.research.google.com/github/vincekurtz/basic-robot-manipulation/blob/main/01_colab-intro.ipynb)

### Simulation notebook

- Download and install dependencies
- Run simulation with meshcat
- Moving the robot arm with sliders
- Try to pick up the block, note how hard it is

### Control System details notebook

- Display control system diagram for the kinova-station
- Explain all the input and output ports
- Sending commands programmatically
- Challenges:
    - Write functionto send robot end-effector to a specific point
    - Same for going in a circle
    - same for picking up the block if the block is in a known position

### Future notebooks

- Interface with camera/depth image
- Using opencv
- Visual servoing based on color
- Hardware interface (as Jupyter notebook)
