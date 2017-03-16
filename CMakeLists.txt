cmake_minimum_required(VERSION 2.8.3)
project(pepper_automation)

find_package(catkin REQUIRED COMPONENTS
  move_base
  move_base_msgs
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

