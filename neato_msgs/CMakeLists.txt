cmake_minimum_required(VERSION 3.5)
project(neato_msgs)

find_package(ament_cmake REQUIRED)
find_package(rosidl_default_generators REQUIRED)

rosidl_generate_interfaces(${PROJECT_NAME}
  "msg/Button.msg"
  "msg/Sensor.msg"
)

ament_package()
