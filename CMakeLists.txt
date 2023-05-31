cmake_minimum_required(VERSION 3.10.2)
project(panther_msgs)

if(CMAKE_COMPILER_IS_GNUCXX OR CMAKE_CXX_COMPILER_ID MATCHES "Clang")
  add_compile_options(-Wall -Wextra -Wpedantic)
endif()

find_package(ament_cmake REQUIRED)
find_package(builtin_interfaces REQUIRED)
find_package(rosidl_default_generators REQUIRED)

rosidl_generate_interfaces(${PROJECT_NAME}
  "msg/DriverState.msg"
  "msg/FaultFlag.msg"
  "msg/MotorControllerState.msg"
  "msg/MotorState.msg"
  "msg/RuntimeError.msg"
  "msg/ScriptFlag.msg"
)

ament_export_dependencies(rosidl_default_runtime)

ament_package()