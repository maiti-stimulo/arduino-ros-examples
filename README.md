# arduino-ros-examples
Set of examples of to learn the interface between ROS and Arduino

##Dependecies
To run the examples you need both the [Arduino](https://www.arduino.cc) and [ROS Kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu), as well as two extra packages not shipped with the ROS Desktop-full installation:
```shell 
sudo apt-get install ros-kinetic-rosserial-arduino
```
```shell 
$ sudo apt-get install ros-kinetic-rosserial-python
```
*Note: Examples also run correctly with ROS Indigo*

##Run
1. Load The Arduino code to your board with the Arduino IDE
2. Execute the launch file: 
```shell 
$ roslaunch arduino_ros_examples oscillator.launch
```
