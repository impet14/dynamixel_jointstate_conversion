cmake_minimum_required(VERSION 2.8.3)
project(dynamixel_jointstate_conversion)

find_package(catkin REQUIRED COMPONENTS
  dynamixel_msgs
  sensor_msgs
)

catkin_package()
