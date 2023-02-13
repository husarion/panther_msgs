cmake_minimum_required(VERSION 3.0.2)
project(panther_msgs)

find_package(catkin REQUIRED COMPONENTS message_generation std_msgs)

add_message_files(
  DIRECTORY msg
  FILES
  DriverState.msg
  FaultFlag.msg
  IOState.msg
  LEDAnimation.msg
  LEDImageAnimation.msg
  MotorControllerState.msg
  MotorState.msg
  RuntimeError.msg
  ScriptFlag.msg
  SystemStatus.msg
)

add_service_files(
  DIRECTORY srv
  FILES
  SetLEDAnimation.srv
  SetLEDBrightness.srv
  SetLEDImageAnimation.srv
)

generate_messages(DEPENDENCIES std_msgs)

catkin_package(CATKIN_DEPENDS message_runtime std_msgs)