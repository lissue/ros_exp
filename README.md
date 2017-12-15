# **Experiment with ROS**

## 1. Installation

### Kinetic: 

http://wiki.ros.org/kinetic/Installation/Ubuntu

### Turtlebot:

`ros-kinetic-turtlebot-gazebo` doesn't include the teleop package, it needs to be installed with `ros-kinetic-turtlebot`

Gazebo and Turtlebot use `python2`. If Anaconda is installed (which usually defaults to `python3`), a conda environment should be created and used:

```
conda create -n ros python=2.7
```

Activate the environment and install `catking_pkg`, `catkin_pkg`, `defusedxml`, `numpy`

Otherwise ~/.bashrc needs to be editted.

## 2. Data Visualization

The data visualization works fine with `python3`.

### Publish data frames
`rqt_bag`

### Visualize
`rviz`