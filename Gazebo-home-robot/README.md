# Gazebo-home-robot

This is the first project of the Udacity's Nanodegree: robotic software engineer.
In this project, three main functionalities of Gazebo are explored:

- adding a model: a robot with two wheels
- adding a building: a simple office
- adding a plugin: a message is displayed while launching the Gazebo world

## Compiling and running ##

``` 
git clone https://github.com/mounalbaccouch/Gazebo-home-robot
cd Gazebo-home-robot/
mkdir build/
cd build/
cmake ../
make
cd ..
export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:<path_to_the_cloned_repo>/Gazebo-home-robot/build
gazebo world/robot-in-building
```
