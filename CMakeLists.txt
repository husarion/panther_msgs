cmake_minimum_required(VERSION 3.0.2)
project(panther_msgs)

find_package(catkin REQUIRED COMPONENTS message_generation std_msgs)

add_message_files(
  DIRECTORY msg
  FILES
  LightsMessage.msg
  DriverState.msg
  MotorControllerState.msg
  MotorState.msg
  FaultFlag.msg
  RuntimeError.msg
  ScriptFlag.msg
  SystemStatus.msg
  LEDAnimation.msg)

add_service_files(
  DIRECTORY srv
  FILES
  SetLEDBrightness.srv
  SetLEDAnimation.srv
  SetLEDImageAnimation.srv
)

generate_messages(DEPENDENCIES std_msgs)

catkin_package(CATKIN_DEPENDS message_runtime std_msgs)