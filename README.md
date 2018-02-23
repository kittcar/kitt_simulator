# kitt_simulator
Gazebo simulation of the Kitt Platform.

# Requirements:

- ROS Kinetic
- Gazebo 7
- ros-kinectic-filters
- ros-kinectic-laser-geometry
- kit_base https://github.com/kittcar/kitt_base
- kit_ros https://github.com/kittcar/kitt_ros

# How to:

To launch kitt robot on an empty world:
```
$ roslaunch kitt_gazebo empty_world.launch 
```
To launch kitt robot on the test world:
```
$ roslaunch kitt_gazebo test_world.launch 
```
