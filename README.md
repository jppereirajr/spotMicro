# Spot Micro Quadruped Project
Great work @mike4192

This is a fork of the original @mike4192 project, upgraded to work will ROS NOETIC and UBUNTU 20.04
___________________________
##  NOETIC version

Version for UBUNTU 20.4 and ROS NOETIC, both of them LTS version, **with support until 2025**.
Furthermore, NOETIC uses python 3 by default, once python 2.7 is deprecated.

It is **100% functional**, resulting faster and with long term support, also it will make much easer migrate to ROS 2 (ros-bridge), if it is the choice.

**UBUNTU 20.4 64 bits (desktop / raspberry pi (server version))**

### INSTALL ROS NOETIC UBUNTU 20.4 64 bits
http://wiki.ros.org/noetic/Installation/Ubuntu

**NOTE**  use ros-noetic-desktop option
```
sudo apt install ros-noetic-desktop
```


##### Additional packages
```
sudo apt install python3-catkin python3-catkin-pkg python3-catkin-pkg-modules python3-catkin-tools
sudo apt install libi2c-dev i2c-tools python3-smbus python3-rpi.gpio
sudo apt install qtbase5-dev
sudo apt install ros-noetic-tf2-eigen 
sudo apt install ros-noetic-joy
sudo apt install ros-noetic-hector-slam

pip3 install osrf-pycommon
```
##### Additional packages from source

###### ROS RPLIDAR
http://wiki.ros.org/rplidar

##### ADD ubuntu user to i2c group 
```
sudo usermod -a -G i2c ubuntu
logout
```


## Future Work

Incorporate a Intel realsense R300 to achieve 3D mapping via SLAM, to avoid obstacles, recognize hands commands and recognize faces.



## REFERENCE

#### NOETIC INSTALL - UBUNTU 20.4
http://wiki.ros.org/noetic/Installation/Ubuntu

#### MIGRATION TO NOETIC
http://wiki.ros.org/noetic/Migration

____________________________
### ORIGINAL PROJECT

https://github.com/mike4192/spotMicro

![Spot Micro Walking](assets/spot_micro_walking.gif)
![RVIZ](assets/rviz_animation.gif)
![slam](assets/spot_micro_slam.gif)

Video of robot: https://www.youtube.com/watch?v=S-uzWG9Z-5E





